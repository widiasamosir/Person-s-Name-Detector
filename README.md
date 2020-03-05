# Person-s-Name-Detector

**run demo.ipynb at jupyter**

run this code at that source code
***
```python
test_string = 'Washing Hand'
test_predict = np.expand_dims([char2id[char] for char in test_string],0)
test_predict = pad_sequences(test_predict, maxlen=40, padding='post')'''
output = model.predict(test_predict)
print(test_string,'is a',label_dict[np.argmax(output)])

```
***


>change text_string if you want to test another strings
