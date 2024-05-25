# Multithreaded Image Recoloring

This Java application demonstrates multithreading by recoloring images using multiple threads. It divides the image processing task into smaller regions and assigns each region to a separate thread, thereby improving processing speed by utilizing multiple CPU cores effectively.

## Features

- **Multithreaded Processing**: Utilizes multiple threads to recolor different sections of the image concurrently.
- **Thread Safety**: Ensures thread safety using proper synchronization techniques.
- **Customizable Thread Count**: Allows customization of the number of threads for parallel processing.

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/multithreaded-image-recoloring.git
    ```

2. Navigate to the project directory:

    ```bash
    cd multithreaded-image-recoloring
    ```

3. Compile the Java source code:

    ```bash
    javac Main.java
    ```

4. Run the application:

    ```bash
    java Main
    ```

5. View the recolored image in the output directory.

## Requirements

- Java Development Kit (JDK) installed on your system.
- Input image file in JPEG format placed in the `resources` directory.

## Configuration

- Adjust the `SOURCE_FILE` and `DESTINATION_FILE` constants in `Main.java` to specify the input and output file paths.
- Modify the `numberOfThreads` parameter in the `main` method of `Main.java` to customize the number of threads used for processing.

## Credits

This project is developed by [Yaroslav Prozorov].

## License

This project is licensed under the [MIT License](LICENSE).
