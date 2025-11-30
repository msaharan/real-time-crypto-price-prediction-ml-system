## Predictor service

## How to train a model in dev mode

```sh
cp .env.local .env.local
```
and replace placeholder with the mlflow user and password.

Then you can manually trigger the training with
```sh
uv run predictor/src/train.py
```