# ❌ Incorrect Predictions

This folder contains images where the DICE model incorrectly predicted the dice value.

These images need relabeling for training DICE 2.0.

## Format
- Image files: `{timestamp}.jpg`
- Metadata files: `{timestamp}.json`

## Metadata Structure
```json
{
  "timestamp": "1234567890",
  "prediction": 5,
  "confidence": 0.78,
  "vote": "INCORRECT",
  "actual": null,
  "savedAt": "2024-01-01T00:00:00Z",
  "source": "realdice.org"
}
```

## Relabeling Process
Images in this folder should be manually reviewed and labeled with the correct dice values for retraining.