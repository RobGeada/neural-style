# neural-style

## About
This is a modified version of Anish Athalye's implementation of [neural-style](https://github.com/anishathalye/neural-style). Specifically, I have changed the `stylize.py` script to allow for the saving and loading of trained models. The full details of these changes are outlined [here](https://github.com/RobGeada/neural-style/commit/e1cacb552c44203f866c93a7d5a894353877fb07#diff-efc232162beac9514aca8b8991751a4a).


## Citation

If you use this implementation in your work, please cite the following:

```
@misc{athalye2015neuralstyle,
  author = {Anish Athalye},
  title = {Neural Style},
  year = {2015},
  howpublished = {\url{https://github.com/anishathalye/neural-style}},
  note = {commit xxxxxxx}
}
```

## License

Copyright (c) 2015-2017 Anish Athalye. Released under GPLv3. See
[LICENSE.txt][license] for details.

[net]: http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat
[paper]: http://arxiv.org/pdf/1508.06576v2.pdf
[l-bfgs]: https://en.wikipedia.org/wiki/Limited-memory_BFGS
[adam]: http://arxiv.org/abs/1412.6980
[ad]: https://en.wikipedia.org/wiki/Automatic_differentiation
[lengstrom-fast-style-transfer]: https://github.com/lengstrom/fast-style-transfer
[fast-neural-style]: https://arxiv.org/pdf/1603.08155v1.pdf
[license]: LICENSE.txt
