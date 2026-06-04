# HEIC to JPEG Converter

## Introduction

This Python script, `heic_to_jpeg.py`, is designed to convert HEIC (High-Efficiency Image Format) files to JPEG format. Before using the script, ensure that you have installed the required packages using pip.

## Prerequisites

1. **Install Pillow, pillow-heif and tqdm package:**

    ```bash
    pip install Pillow pillow-heif tqdm
    ```

## Usage

1. **Download the Script:**

    Download the `heic_to_jpeg.py` script to your local machine.

2. **Edit the Script:**

    Open the script in a text editor of your choice. Replace the `folder_dir` variable with the path to the folder containing your HEIC files.

    ```python
    # Replace 'your_custom_folder_path' with the actual path to your folder containing HEIC files
    folder_dir = 'your_custom_folder_path'
    ```

3. **Run the Script:**

    Open a terminal and navigate to the directory where the script is located. Run the following command:

    ```bash
    python heic_to_jpeg.py
    ```

4. **Optional: Keep Original HEIC Files:**

    By default, the script will remove the original .heic file after successfully converting it to JPEG. If you want to retain the original .heic files, follow these steps:

    - Locate the following line in the script:

        ```python
        os.remove(input_file)
        ```

    - Comment out the line by adding a `#` at the beginning:

        ```python
        # os.remove(input_file)
        ```

    This change will keep the original .heic file in the specified folder.

## Important Note

- The script will overwrite existing JPEG files with the same name in the specified folder.
- Ensure that you have a backup of your HEIC files before running the script, especially if you choose to remove the original .heic files.

## Credits

This converter was made by [nick8592](https://github.com/nick8592), and was license-free, so I used the converter in this repo with sufficient credit.
