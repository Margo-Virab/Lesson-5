#Իրականացնել պարզ վիկտորինա-խաղ, որը կպարունակի հարցերի և պատասխանների ցուցակներ(lists)։ Խաղը սկսելուց պատահական սկզբունքով հարց պետք է տրվի խաղացողին և պատասխանից կախված խաղի վերջում հայտնվի ճիշտ պատասխանների քանակը։ Հարցերը չպետք է կրկնվեն։

from random import sample
Question1= ['Who has won more tennis grand slam titles, Venus Williams or Serena Williams?|Serena Williams','How many colors are there in the rainbow?|7', 'What country is responsible for creating the Olympic Games?|Greece', 'How many legs does a spider have?|8', 'How many teeth does an adult human have?|32']
Question = sample(Question1, 5)
right_answer=0
for i in range(len(Question)):
    Q=Question[i].split('|')
    s=input(Q[0])
 
    if  s.lower()==Q[1].lower():
        print("Correct")
        right_answer=right_answer+1
    else:
        print("Wrong answer. The right answer is:", Q[1])
print("Right answers are ", right_answer, "out of 5")

#Իրականացնել պարզագույն բառարան, որը ֆայլից կկարդա բառերի համախումբ՝ անգերեն-հայերի բառերի թարգմանությամբ։ Բառերը կարող են լինել Python keyword-ներ, statement-ներ և այլ համակարգչային գիտությանը վերաբերվող բառեր։ Օբյեկտը, որի մեջ պետք է պահեք բառերը, կարող է լինել dictionary։

D={'and':'Տրամաբանական օպերատոր',
   'as':'Ծածկանուն ստեղծելու համար',
   'assert':'Վրիպազերծման համար',
   'break':'Հանգույցից դուրս գալ',
   'class':'Դաս սահմանելու համար',
   'continue':'Շարունակելու համար հանգույցի հաջորդ կրկնությունը',
   'def':'Ֆունկցիա սահմանելու համար',
   'del':'Օբյեկտը ջնջելու համար',
   'elif':'Օգտագործվում է պայմանական հայտարարություններում, նույնը, ինչ եթե',
   'else':'Օգտագործվում է պայմանական հայտարարություններում',
   'exept':'Օգտագործվում է բացառություններով, ինչ անել, երբ բացառություն է տեղի ունենում',
   'False':'Բուլյան արժեք, համեմատական գործողությունների արդյունք'}
key=input("Enter keyword: ")
print(D.get(key))


#Տրված է հետևյալ ֆունկցիան def myfunc(alist): . . . . return len(alist)։ dis module-ի օգնությամբ դուրս բերել բայթ կոդի ներկայացումը և նկարագրել բոլոր դաշտերը (Python byte-code)։

import dis
def myfunc(alist):
    return len(alist)
dis.dis(myfunc)


