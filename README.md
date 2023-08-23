# Al-Qur'an API Documentation
## Base URL
```
https://api.quran.gading.dev
```

## Get list all surah
### Request
Method: GET <br/>
Authentication: none
```
endpoint: /surah
``` 
<a href="https://api.quran.gading.dev/surah" target="_blank">Run Example</a>

## Get Surah By Id
### Request
Method: GET <br/>
Authentication: none
```
endpoint: surah/{surah_id}
example: surah/{1} // result surah Al-fatihah
```
<a href="https://api.quran.gading.dev/surah/1" target="_blank">Run Example</a>

## Get Ayah in Surah By Id
### Request
Method: GET <br/>
Authentication: none 
```
endpoint: surah/{surah_id}/{ayah_id}
example: surah/1/7 //result surah Al-fatihah ayah 7
```
<a href="https://api.quran.gading.dev/surah/1/7" target="_blank">Run Example</a>

## Get Juz By Id
### Request
Method: GET <br/>
Authentication: none 
```
endpoint: juz/{juz_id}
example: juz/1 //result Juz 1
```
<a href="https://api.quran.gading.dev/juz/1" target="_blank">Run Example</a>

## Reference
API Created By [gadingnst](https://github.com/gadingnst/quran-api)
