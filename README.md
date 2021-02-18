# cueback-backlog

The tasks contained in this repository are:

## Unsplash

Unsplash is aimed to leverage stock image search to add stock images to every memory created without an attached image. The script is provided as a simple python script. The script takes in one parameter - a memory title. If the keyword returns no results the script will simply return a random photograph. Run this script with 

```python
python unsplash.py keyword
```

The results are returned in a json schema following

```json
{
    "link" : "......"
    "author" : "....."
}
```
