# EfficientNet-B3: Image Classifier

The [EfficientNet model](https://aws.amazon.com/marketplace/pp/prodview-b4jqie4ebeo4y)
provides top-k category predictions out of the 1000 classes on [ImageNet](http://www.image-net.org)
based on the [EfficientNet B3 algorithm](http://proceedings.mlr.press/v97/tan19a/tan19a.pdf).
This network provides state of the art accuracy on [ImageNet](http://www.image-net.org) and at the same time it provides a smaller model and faster inference than other models such as `ConvNets`.
[Launch on SageMaker](https://aws.amazon.com/marketplace/pp/prodview-b4jqie4ebeo4y).

The [EfficientNet algorithm](https://aws.amazon.com/marketplace/pp/prodview-ezdqmlf7aumf2)
allows you to also train custom models by fine-tunning (transfer learning) the ImageNet weights to make predictions in custom labels.
[Launch on SageMaker](https://aws.amazon.com/marketplace/pp/prodview-ezdqmlf7aumf2).

Features:

- State of the art accuracy on the ImageNet validation dataset:
    - Top-1 Accuracy (err): `82.242 (17.758)`
    - Top-5 Accuracy (err): `96.114 (3.886)`
- Fine-tunning the ImageNet model to custom labels
- Provides smaller and faster inference than `ConvNets`
- Flexible endpoint to classify one or multiple images with configurable parameters
- Only pay for what you use with a simple metered pricing model
- Same price independent of the resources (`memory/cpu/gpu`) used

Learn how to how to [train a custom model](/model/efficientnet-b3/train),
[launch this model in AWS SageMaker](/model/efficientnet-b3/getting-started),
see [examples](/model/efficientnet-b3/examples) from the base model.

## Pricing

This model has a fee of `0.15` dollars per hour.
You will incur costs for software use **only** for as long as the endpoint is running.

AWS infrastructure costs are independent and in addition to the costs of the software
and it depends on the instance type selected to host the algorithm.
