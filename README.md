# Duplicated Image Cleaner

Duplicated Image Cleaner is a command-line tool for detecting and removing duplicate or similar images in a directory.

## Installation

You can install the package using pip:

```
pip install duplicated-image-cleaner
```

## Usage

To run the `delete_duplicates` command, use the following syntax:

```
delete_duplicates [OPTIONS] DIRECTORY
```

### Options

- `--dry_run`: Perform a dry run to simulate the deletion of duplicate images without actually deleting them.

- `--include_similar`: Delete similar images in addition to exact duplicates.

### Examples

To perform a dry run and list the duplicate images without deleting them:

```
delete_duplicates --dry_run DIRECTORY
```

To delete exact duplicates without a dry run:

```
delete_duplicates DIRECTORY
```

To delete exact duplicates and similar images:

```
delete_duplicates --include_similar DIRECTORY
```

**Note: Exercise caution when using the script, especially when deleting images. Always double-check the command and make sure you have a backup of your images before running the script.**

## License

This project is licensed under the [MIT License](LICENSE).
