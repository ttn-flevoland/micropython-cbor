# micropython-cbor

More info about CBOR http://cbor.io

Changed for Micropython, original source: https://github.com/brianolson/cbor_py/blob/master/cbor/cbor.py

Use:
```

  import cbor

  value_object =  {'temperature': temperature, 'pressure': pressure }
  cbor_value_object = cbor.dumps(value_object)

```
