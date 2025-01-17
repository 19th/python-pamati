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

Lai pārbaudīt tipu izmanto funkciju `type`
```python
type("Šeit ir teksts") # string
type(12345) # int
type(3.14) # float
```

Lai konvertēt tipu izmanto funkcijas `str`, `int`,  `float`, `bool`, 
```python
str(12345) # konvertējam skaitli uz tekstu
int("1188") # konvertējam tekstu uz skaitli
float("3.14") # konvertējam daļskaitli uz tekstu
```

#### Skaitliskie mainīgie 🔟

Izmantoti pārsvarā lai veikt matemātiskas operācijas.
```python
x = 747
y = -15

pi = 3.141592
fi = 1.6180339

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

Lai konvertēt tipu izmanto funkcijas `str`, `int`,  `float`, `bool`, 
```python
str(12345) # konvertējam skaitli uz tekstu
int("1188") # konvertējam tekstu uz skaitli
float("3.14") # konvertējam daļskaitli uz tekstu
```

### 


## Nosacījumi (zarošana) 🚦


## Cikli 🔁
Ciklus izmantoto lai atkārto kodu vairākas reizes. "For" cikls ir vairāk domāts izmantošanai, kad ir zinams cik reizes veikt atkārtojums, bet "while" izmanto kad ir nosacījums kurš nosaka atkārtojumu reizes.

### For cikls
Atkārtot noteiktu reižu skaitu.
```python
for indeks in range(6):
  print(indeks) # tiks izdrukāts 0 1 2 3 4 5 6
```

Atkārtot priekš katrā simbola tekstā
```python
teksts = "Sveiki!"
for simbols in teksts:
  print(simbols) # tiks izdrukāts S v e i k i !
```

Atkārtot noteiktu reižu skaitu, bet sākt indeksu no divnieka
```python
for indeks in range(2, 6):
  print(indeks) # tiks izdrukāts 2 3 4 5 6
```

### While cikls



## Funkcijas


## Saraksti


## Vārdnīcas


## Objekta Orientēta Programmēšana (OOP)


