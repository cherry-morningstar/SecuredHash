  【SecuredHash】
【Author : CHERRY】

This Tool Make Your Text More Secure With KeyHash Feature.
Also, Generate Hashes(SHA1,SHA224,SHA256,SHA384,SHA512,BLAKE2b,BLAKE2s,MD5).
Generated Hashes And keyHashes are Stored In HashData.db Database.
You Also Share Secret Messages With Your Freinds Using ShareData Feature.

【Installation】

git clone https://github.com/CherryAnnon/SecuredHash

pkg install python

pip install -r requirements.txt

python Hash.py


【Usage】

1.Hash 2.DeHash 3.ShareHash
Generate Hash :
(!) 1-8 For Simple Hashes And 0 For KeyHash

DeHash :-
1.Hash
Hash :Past Your Hash (If the Hash is in the database then it will give you the result otherwise it will not give anything)

2. KeyHash
Hash :Past Your Hashes
Key :Hash/00000000.key (When .key Is In The Hash Folder Otherwise Where Your Key Have)

3. ShareHash :-
First Type 1 For Create ShareData.db (Select All Hashes From Your DataBase Type * In Hash Field, Type * In Both Field For All KeyHashes)
Then Give It To Your Friend
Freind: Type 2 For Merge Datas
Now Your Friend Also Decrypt KeyHashes With Key.

