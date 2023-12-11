# python-code1
#how to create a class#

class Employee:
    def __init__(self,name,id,address):
        self.name=name
        self.id=id
        self.address=address

class Typeofemp(Employee):
    def __init__(self, name, id, address, email):
        super().__init__(name, id, address)
        self.email=email
emp=Typeofemp(name="Ankur",id=1231,address="Jalandhar",email="1234@")
print("id of employee: ",emp.id)
print("name: ",emp.name)
print("address: ",emp.address)
print("email: ",emp.email)

        ####################

class student:
    def __init__(self,name,age):
        self.name=name
        self.age=age
        self.group="ECE"
        self.report="fail"
    def setDetails(self,__group,__report):
        self.__group=__group
        self.__report=__report
    def getDetails(self):
        print(self.name,self.age,self.__group,self.__report)

print("Student Report Card")
s1 = student('Abcd','19')
s1.setDetails("CSC","Pass")
s1.getDetails()

