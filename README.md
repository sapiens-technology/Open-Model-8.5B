![Banner](banner-open-model.jpeg)

# Open-Model-8.5B

<div align="justify">
  <p>The <strong>Open-Model-8.5B</strong> is a proprietary language model with 8.5 billion parameters, compiled and packaged according to <strong>Sapiens Technology®️</strong>'s <i>SAPI</i> standard. It is a general-purpose model made freely available at no cost so that <strong>Sapiens Technology®️</strong> <i>customers</i> and <i>users</i> can customize it with their own data through post-training techniques, such as continued pretraining and/or fine-tuning. To perform post-training and inference on this and any other <strong>Sapiens Technology®️</strong> model, installation of our <code>SapiLM</code> execution engine is required in an environment running <code>Python 3.11</code>.</p>
  <p>The Open-Model family models are not intended to be frontier models. They were trained solely to communicate fluently and naturally in multiple languages, including English, Portuguese, and Spanish, eliminating the main bottleneck in model training: learning linguistic and semantic patterns.</p>
  <p>Their purpose is to facilitate the development of proprietary and specialized models without requiring developers to train a model from scratch to learn linguistic patterns before specializing it. Models in this family have already been fine-tuned to support chat-based conversations and follow simple instructions with a low level of complexity.</p>
  <p>These characteristics make them ideal for creating customized models without the noise associated with highly general-purpose training data.</p>
</div>

## Download model

```bash
sapilm --get open-model-8.5b
```

## Load model

```bash
sapilm --load open-model-8.5b
```

## Remove model

```bash
sapilm --remove open-model-8.5b
```

## Contributing

<div align="justify">
  <p>We do not accept contributions that could result in the modification of the original model, under any circumstances. Only members of the <strong>Sapiens Technology®️</strong> research and development team may contribute to the original model in this repository; this includes weights, code, and documentation.</p>
</div>

## License

<div align="justify">
  <p>The downloading, copying, and distribution of this model are permitted for any <strong>Sapiens Technology®️</strong> subscription customer. Our customers are free to further train this model using continued pretraining and fine-tuning techniques natively supported by the <code>SapiLM</code> engine. <strong>Sapiens Technology®️</strong> subscription customers are authorized to use this model as they see fit, without any restrictions or limitations.</p>
  <p>Users and developers who are <strong>not</strong> <strong>Sapiens Technology®️</strong> subscribers are not authorized to download, further train, distribute, and/or modify this model. Failure to comply with these guidelines may result in legal action pursued by our team of lawyers.</p>
</div>
