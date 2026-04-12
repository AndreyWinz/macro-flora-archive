Use this Python script as a converter of HEIC/HEIF images to PNG
-
## Requirements

This script requires the following libraries to be installed:

- `Pillow`
- `pillow-heif`

You can install them by running:

```
pip install -r requirements.txt
```

## Usage

1. Place all the HEIC files you want to convert in the `heic_img` directory.

2. Run the script `main.py`:

   ```
   python main.py
   ```

3. All HEIC files in the `heic_img` directory will be converted to PNG format and saved in the same directory with the same name but with the `.png` extension.

## Notes

- If you want to convert HEIC files in a different directory, modify the `directory` variable in the script to the appropriate directory path.
```python
# set the directory path containing the HEIC files
directory = 'heic_img'
```

## Credits
Credits to [@victorlvl47](https://github.com/victorlvl47) for the HEIC/HEIF to PNG converter.
