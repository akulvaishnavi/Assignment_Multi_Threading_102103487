# Program Description: Multi-Threading

The Python program demonstrates the impact of using multiple threads on the time taken to perform matrix multiplication. It also measures CPU utilization during the matrix multiplication process.

# Function Explanations:

    create_random_matrices(num, size):
        Description: Generates a list of random matrices.
        Parameters:
            num: Number of matrices to generate.
            size: Size of the matrices.
        Returns: List of random matrices.

    multiply_matrices_task(matrices):
        Description: Multiplies a list of matrices.
        Parameters:
            matrices: List of matrices to multiply.
        Returns: Resultant matrix.

    perform_multiplication_with_threads(num_threads):
        Description: Performs matrix multiplication using multiple threads.
        Parameters:
            num_threads: Number of threads to use.
        Returns: Time taken for the multiplication process.

    measure_cpu_utilization(duration):
        Description: Measures CPU utilization.
        Parameters:
            duration: Duration of time to measure CPU utilization.
        Returns: List of CPU utilization values over the specified duration.
