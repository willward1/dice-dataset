# ✅ Correct Predictions

This folder contains images where the DICE model correctly predicted the dice value.

## Format
- Image files: `{timestamp}.jpg`
- Metadata files: `{timestamp}.json`

## Metadata Structure
```json
{
  "timestamp": "1234567890",
  "prediction": 7,
  "confidence": 0.95,
  "vote": "CORRECT",
  "savedAt": "2024-01-01T00:00:00Z",
  "source": "realdice.org"
}
```