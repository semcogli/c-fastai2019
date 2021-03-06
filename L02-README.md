## Tips & tricks

- Cleaning image datasets - remove the top_losses() manually
- Writing Jupyter notebook widgets (e.g. FileDeleter)
- Use CPU for inference on production deployments

## Anki

- How to determine the LR in learning rate finder? <<>> Point with strongest prolonged downward slope.
- What are the possible reasons for issues with training? <<>> { LR, Epochs } x { high, low }
- Training issue: {{ LR high }} means {{ Validation loss is extremely large }} 
- Training issue: {{ LR low }} means {{ error_rate gets better very slowly }}
- Training issue: {{ Training loss > Validation loss}} means {{ underfitting }} means {{ LR is low OR Epochs is low }}
- Training issue: {{ Epochs is high  }} means {{ overfitting }} means {{ error_rate improves and becomes worse }}
- For a properly trained model how does Training loss compare to Validation loss? <<>> Training loss < Validation loss

## Katas

- L02-Kata-SGD

## TODO

- ImageDownloader

## References

- [Lesson material](https://course-v3.fast.ai/videos/?lesson=2)
- [Lesson transcripts](https://github.com/hiromis/notes/blob/master/Lesson2.md)
