# RPS zadanie 1
 
## Zadanie K1 (komputerowe).

Rozważ grę wykorzystującą generator liczb losowych losujący w sposób
niezależny i równomierny liczby losowe z ciągłego przedziału między 1 a 100. Gra zaczyna się z sumą
𝑆 = 0. Pierwszy gracz dodaje do S liczby losowe wygenerowane kolejno z generatora, dopóki 𝑆 > 100,
i zapisuje ostatnią wygenerowaną liczbę 𝑥. Następnie, gracz drugi kontynuuje dodawanie do S liczb
losowych z generatora, dopóki 𝑆 > 200, i zapisuje ostatnią wygenerowaną liczbę 𝑦. Gracz z większą
liczbą wygrywa, np. jeśli 𝑦 > 𝑥, to wygrywa gracz drugi. Czy gra jest sprawiedliwa? Napisz program
symulujący 100,000 gier i oszacuj za jego pomocą, z dokładnością do 3 miejsc po przecinku,
prawdopodobieństwo, że gracz drugi wygra.