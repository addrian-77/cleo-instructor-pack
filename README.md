# Instructor Pack

Acesta este un pachet de moduri **CLEO** open-source facute pentru membrii School Instructors ai serverului de SAMP OG B-Hood

### **Lista cu comenzi:**

##### InstructorCMD
- **/icmd** lista cu comenzile
##### ResponsabilCMD
- **/amenzi <nume>** meniu din care selectam tipul de amenda
- **/teste <id>** meniu din care cerem test / aprobam / dam reminder
##### TesterCMD
- **/tcmd** sau **/testercmd** lista cu comenzi

### Instalare
Modurile se pun in fisierul cleo.
- Pentru **InstructorCMD** este nevoie si de **Instructor CMD.ini** pus in **cleo_saves** 
- Pentru **TesterCMD** este nevoie si de **Tester CMD School Instructors - Testlog.ini** pus in **cleo_saves**

#### Cool features
- In momentul in care folosim ```/sl <id>```, **InstructorCMD** verifica singur daca jucatorul este membru staff / lider / level 50+ si va crea un dialog cu informatiile despre jucator.
- **InstructorCMD** si **ResponsabilCMD** au o functie de confirmare pentru comenzi mai riscante, cum ar fi cele care trimit mesaje pe ```/in``` sau pentru amenzi. Intr-un dialog vor aparea mesajele ce urmeaza sa fie trimise.
- Citirea din fisierele de configurare este facuta incat sa permita mesaje cu mai multe parti
- Bindurile pentru testele de licente pot fi grupate din fisierul **.ini** in orice mod
- Testlogul poate fi editat din fisierul **.ini**, nu este nevoie de restart la joc