#ส่งการบ้าน
Class Diagram 1 
Code
```
@startuml
Mother <|-- Son

Mother : equals()
Son : Mother[] MoneySon


@enduml

```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuVBDByb8BRAfqTLL2CxFuuBo5QmKVFFpKYirDBc0eY1U8aWuEXOY35R9vP2Qbm8q0W00)

Class Diagram 2
Code
```
@startuml

class Bam {
 -Name
 #Lastname
 ~Heir()
 +Body()
}

@enduml

```

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU9ApaaiBbPmIinLgEPIqFLBp4tbKb3sIImkoGCpwpnICuiqDBaKj9toKog1Z5ekBeVKl1IWNW00)

Class Diagram 3
Code
```
@startuml
class Bam {
  {static} Student id
  {abstract} Number()
}
@enduml

```

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKhEIImkLd1Ap5Mevb9Gg0QAbsGcroe4bvIcfEQLA6IcW4GJaufBYXAJIseL_4fparABD3IvQhaSKlDIW2O00000)

Class Diagram 4
Code
```
@startuml

class Bam
Bam --> KFC : lunch
note on link #red: Eat lunch

Bam --> Somtum : Dinner
note right on link #green
	Eat Dinner
end note

@enduml
```


![](http://www.plantuml.com/plantuml/img/HSv12eD030NGTNEA3rrx0HT5MdNJPKymQD31cGnaulsDLDf5u4F-2-cg1RKz9w8fXLhn39byq3GFlCSNMgHTffMa6AC8KfGDT-MvnH3iMlx4fsG_vgYF8gnVfN5PxMyNPHQwdVfgiSmucqITHt_c0000)

Class Diagram 5
Code
```
@startuml

class System << (B,#FF0000) Bam >>
class Date << (D,Green) >>
@enduml
```

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU9ApaaiBbO8hYmkISrLiB5Hq73IKNPpCm02JGMdn5m5Epke4fV4abIm0XSTzwBKr3nDa9H3QbuAq1W0)




# OOAD-WEEK09
Class Diagram
