import hashlib
for i in range (1000):
    inp = "data"+str(i)+"\n";
    hash_object = hashlib.sha256(bytes(inp,'utf-8'))
    hex_dig = hash_object.hexdigest()
    if(hex_dig[0:2]=='00'):
        print(f"{inp} == {hex_dig}")
