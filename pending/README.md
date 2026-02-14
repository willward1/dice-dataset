# ⏳ Pending Predictions

This folder contains dice images that have been captured but not yet voted on.

## Structure
Images are organized by predicted value:
- `pending/1/` - Images predicted as 1
- `pending/2/` - Images predicted as 2
- ...
- `pending/20/` - Images predicted as 20

## Flow
1. When dice are rolled, image saves here immediately
2. When someone votes, image should move to:
   - `correct/{value}/` if vote is CORRECT
   - `incorrect/` if vote is INCORRECT

## Note
These images are awaiting community validation through the voting system on realdice.org