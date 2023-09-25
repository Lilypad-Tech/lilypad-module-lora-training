# LoRA fine tuning of Stable Diffusion 1.5

# Inputs

* SeedEnv = `RANDOM_SEED=42`
* ImagesCID = IPFS CID containing an `images.zip` containing training images (any filenames)

Example:

```
lilypad run lora-inference:v0.0.1 -i ImagesCID=Qm...
```

You can feed the output CID of this job into [`lora-inference`](https://github.com/bacalhau-project/lilypad-module-lora-inference)
