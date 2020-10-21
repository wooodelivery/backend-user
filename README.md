# backend-user

```
git clone
git cd
```

### Install Requirements:

```python
virtualenv -p python3 ./venv
source ./venv/bin/activate
pip3 -r requirements.txt
```

###Running

```python
python run.py
```

####Go to:
```
http://127.0.0.1:4000/api/v1
```


###Try it out:
```json
{
   "type":"Feature",
   "geometry":{
      "type":"Polygon",
      "coordinates":[
         [
            13.4197998046875,
            52.52624809700062
         ],
         [
            13.387527465820312,
            52.53084314728766
         ],
         [
            13.366928100585938,
            52.50535544522142
         ],
         [
            13.419113159179688,
            52.501175722709434
         ],
         [
            13.4197998046875,
            52.52624809700062
         ]
      ]
   }
}
```
```json
{
   "type":"Feature",
   "geometry":{
      "type":"LineString",
      "coordinates":[
         [
            13.420143127441406,
            52.515594085869914
         ],
         [
            13.421173095703125,
            52.50535544522142
         ],
         [
            13.421173095703125,
            52.49532344352079
         ]
      ]
   }
}