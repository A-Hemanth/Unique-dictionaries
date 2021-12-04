# Unique-dictionaries
#Q.6
dict_list=[{'name': 'affirm', 'confidence': 0.9448149204254}, {'name': 'affirm', 'confidence': 0.944814920425415}, {'name': 'inform', 'confidence': 0.9842240810394287}, {'name': 'inform', 'confidence': 0.9842240810394287}] 
dict_list_uniq = []
for data in dict_list:
    if data not in dict_list_uniq:
        dict_list_uniq.append(data)
print(dict_list_uniq)

#OR


dict_list=[{'name': 'affirm', 'confidence': 0.9448149204254}, {'name': 'affirm', 'confidence': 0.944814920425415}, {'name': 'inform', 'confidence': 0.9842240810394287}, {'name': 'inform', 'confidence': 0.9842240810394287}] 
dict_list_updated = [ str(item) for item in dict_list]
unique_set = set(dict_list_updated)
print(unique_set)
