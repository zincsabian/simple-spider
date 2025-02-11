## simple spider

NOTE that this project is for learning.

### reference

1. [ask.py](https://github.com/pengfeng/ask.py?tab=readme-ov-file)

### quick-start

1. python environment
   ``` shell
    conda create --name test python=3.10
    conda activate test

    pip install -r requirements.txt
   ```
2. env config
   ```
    SEARCH_API_KEY=
    SEARCH_PROJECT_KEY=
    SEARCH_API_URL=https://www.googleapis.com/customsearch/v1
   ```

[google custom search](https://developers.google.com/custom-search/v1/overview?hl=zh-cn)

3. run it
   ``` shell
    python demo.py
   ```