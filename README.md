# python-fundamental-training
OOPS Concept
class student:
 def __init__ (self,name,age,id,phone):
        self.name = name
        self.age = age
        self.id = id
        self.phone = phone
 def info(self):
     print(f'{"="*10} Info {"="*10} \nName : {self.name}  \nAge : {self.age} \nid : {self.id}\n{"="*10} Info {"="*10} \nphone {self.phone}')

 def call(self):
     print(f'calling ........  {self.phone}\n')

 def sendmsg(self,msg):
     print(f'\n {msg}\n SENDING .....{self.name}')

s1= student('Santosh',25,71929,9505193232)
s2 =student("ramu",32,71879,9030515078)

s1.info()
print()
s2.info()
s2.call()
s1.call()
s1.sendmsg("Hii\n how ar u")
