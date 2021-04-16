
Principiile SOLID

1. Single Responsability Principle – fiecare clasa ar trebui sa aiba o singura responsabilitate.
2. Open-Closed Principle – fiecare clasa ar trebui sa fie deschisa pentru extindere si închisa pentru modificari.
3. Liskov’s Substitution Principle – orice clasa derivata poate inlocui clasa de baza si codul sa functioneze corect
   în continuare.
4. Interface Segregation Principle – in loc sa avem o interfata cu foarte multe metode, din care doar cateva sunt
   folosite, mai bine avem mai multe interfete mai mici si le folosim doar pe cele necesare.
5. Dependency Inversion Principle – daca o clasa are o dependenta, aceasta dependenta ar trebui sa fie o
   interfata, nu o clasa concreta – acest principiu incurajeaza decuplarea claselor si e necesar pentru testarea unitara.