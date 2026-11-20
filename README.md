# Ultrasound Pipeline Test Harness

A planned Python regression-testing prototype for ultrasound image-processing pipelines.

The goal is to compare pipeline outputs against a saved baseline using synthetic or approved de-identified data. The prototype may include image comparisons such as SSIM and PSNR, selected-region speckle contrast checks, runtime measurements, and a summary report.

## Planned workflow

1. Run a Python processing pipeline on test data.
2. Compare outputs and metrics with a baseline.
3. Flag unexpected changes for manual review.
4. Explore running the tests automatically on pull requests with GitHub Actions.

## Privacy and scope

This public repository will not contain patient data or proprietary employer code. The project is for engineering evaluation and is not intended for clinical use.

## Status

Planning stage. Implementation has not started.
