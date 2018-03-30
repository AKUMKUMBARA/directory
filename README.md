# directory

Directory = {'Jane Doe': '+27 555 5367',
    'John Smith': '+27 555 6254',
    'Bob Stone': '+27 555 5689'}
Directory['Jane Doe']= '+27 555 1024'
Directory['Anna Cooper']= '+27 555 3237'
print (Directory)

print ('semua value:%s'%Directory.values())

for key in Directory.items():
    print('%s : %s' % (key))

