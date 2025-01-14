# Python pamati

## Ievads/izvads ↔️
### Izvads ➡️
Lai izdrukāt datus konsolē, tiek izmantota `print` iebuvēta funkcija.
```python
print("Šodien ir jauka diena")
```

Izdrukāt vairāk datu var izmantojot komatu. Starp vērtībam tiks izdrukāts viens tukš simbols.
```python
print("Temperatūra ārā ir", 14, "grādi") # Temperatūra ārā ir 14 grādi
```

Lai izdrukāt tekstu un mainīgo kombināciju var izmantot f konstrukciju un ierakstot mainīgus iekavas {}
```python
vards = "Aleksejs"
print(f"Sveiks, {vards}!") # Sveiks, Aleksejs
```

### Ievads ⬅️
Lai konsolē iegūt datus no lietotāja izmanto iebūvētu komandu `input`.
```python
vards = input("Ievadi savu vārdu: ")
```

Dati no konsolēs nāk vienmēr ar tipu `string` (teksts), bet ja nepieciešams iegūt no lietotāja ciparu - to nepieciešams konvertēt.
```python
vecums = int(input("Ievadi savu vecumu: "))
```

## Mainīgie 💾
Mainīgie tiek izmantoti lai glabāt datus un veikt operācijas ar tiem. Dati varētu būt vairākos tipos: teksts, skaitlis, daļskaitlis, būla vērtība (jā/nē) un citi. Katram mainīgam ir nosaukums. Izveidot (definēt) mainīgo var norādot to vārdu un sākotnēju vērtību. Veicot operācijas ar mainīgo tiek izmantots tas nosaukums.

### Veidošana (inicializācija, definēšana)
Veidošana notiek norādot nosaukum, vienadības zīmi un vērtību. Kad mainīgais ir izveidots, to var izmantot zemāk kodā.
```python
sveiciens = "Esi sveicināts!"
latvijas_regionu_skaits = 4
eur_uz_usd = 1.02
```

### Mainīgo tipi
Dati tiek glabāti atmiņā optimizēta veidā, tāpēc datiem varētu būt vairāki datu tipi, kuri ļauj veikt noteiktas operācijas.
- `string`, ir teksta tips un ļauj salimēt kopā, griezt, atkārtot un citas operācijas
- `int`, ir vesela skaitļa tips un ļauj veikt matematiskas operācijas
- `float`, ir dalīta skaitļa tips un ļauj arī veikt matematiskas operācijas 
- `bool`, var saturēt tikai `True` vai `False`

#### Skaitliskie mainīgie 🔟

Izmantoti pārsvarā lai veikt matemātiskas operācijas.
```python
a = 5 + 7
b = 3.14 - 2.71
c = 6 * 10
d = 36 / 6
```

Lai palielināt mainīgo var izmantot pilnu vai saisināto konstrukciju.
```python
a = a + 10 # palielināt `a` mainīgo uz 10
a += a + 10 # palielināt `a` mainīgo uz 10, bet saisināta versija
```

Lai uzzināt atlikumu no dalīšanas izmanto procentu simbolu.
```python
a = 5
atlikums = a % 2 # a ir vienads 1
```

#### Teksta mainīgie 💬
Teksta mainīgiem ir plašs pielietojums.

```python
teksts = "Viena rinda"

ari_teksts = """
Vairākas rindas
"""

tuks_teksts = ""
```

#### Būla mainīgie 👍/👎
Var saturēt tikai `True` vai `False`.

```python
ir_sarkans = False
ir_pozitivs = a > 0
ir_para_skaitlis = a % 2 == 1
```

### Konvertācija 
Operācijas, kas ir iespējamas ar vienu datu tipu varētu būt neloģiskas un neiespējamas ar citu.


### 


## Nosacījumi (zarošana) 🚦


## Cikli 🔁

### For cikls

### While cikls



## Funkcijas


## Saraksti


## Vārdnīcas


## Objekta Orientēta Programmēšana (OOP)


