# Ya Mozzza Wake Word Model

Custom microWakeWord model for Home Assistant Voice PE.

## Usage

Add to your ESPHome Voice PE configuration:

```yaml
micro_wake_word:
  models:
    - model: https://github.com/amhash/ya-mozzza-wakeword/releases/download/v1.0.0/ya_mozzza.json
      id: ya_mozzza
```

## Training Details

- **Wake word**: "Yah Moz-zah" (يا موزة)
- **Samples**: 2000 synthetic samples from 3 English voices
- **Framework**: microWakeWord
- **Model size**: ~75KB

## Files

- `ya_mozzza.tflite` - The TFLite model file
- `ya_mozzza.json` - Model manifest for ESPHome
