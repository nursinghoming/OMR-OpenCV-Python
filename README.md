# omr
Optical Mark AnswerSheets

## Usage
```sh
$ python2main.py --help
usage: main.py [-h] --input INPUT [--output OUTPUT] [--show]

optional arguments:
  -h, --help       show this help message and exit
  --input INPUT    Input image filename
  --output OUTPUT  Output image filename
  --show           Displays annotated image
```

## Example

```sh
$ python main.py --input img/test.jpg  --output /tmp/results.png --show

Q1: A
Q2: C
Q3: C
Q4: E
Q5: A
Q6: B
Q7: A
Q8: C
Q9: D
Q10: E
