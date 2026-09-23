# Project Log

## September 23, 2026 — Repository and HPC setup

- Created the GitHub repository for the cotton boll detection project.
- Cloned the repository to `/fs1/scratch/aqsamuz/cotton-boll-detection-yolo`.
- Configured Git username and email on the NMSU Discovery HPC.
- Connected the HPC to GitHub using SSH authentication.
- Updated `.gitignore` to exclude datasets, model weights, raw terminal logs, and generated YOLO results.
- Started keeping local terminal logs in the `logs` directory.
- Kept the public cotton dataset separately at `/fs1/scratch/aqsamuz/YOLO/public_cotton`.

## Next steps

- Test YOLO training with a small sample dataset.
- Create a reproducible HPC training script.
- Document the training, validation, and testing workflow.
- Save selected results and figures.
