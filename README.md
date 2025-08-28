# Usage

```bash
git clone https://github.com/ArthurDelannoyazerty/embedding-projector-standalone.git
cd embedding-projector-standalone
python -m http.server 8001
```
Then got to :

`http://localhost:8001`

If you have a config file in the `oss_data` folder, add the config filepath to the url, like : 

`http://progpu104:8001/?config=./oss_data/custom_config.json`
