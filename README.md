# Python pamati

## Ievads/izvads
### Izvads
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

### Ievads
Lai konsolē iegūt datus no lietotāja izmanto iebūvētu komandu `input`.
```python
vards = input("Ievadi savu vārdu: ")
```

Dati no konsolēs nāk vienmēr ar tipu `string` (teksts), bet ja nepieciešams iegūt no lietotāja ciparu - to nepieciešams konvertēt.
```python
vecums = int(input("Ievadi savu vecumu: "))
```

## Mainīgie
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

#### Skaitliskie mainīgie
```python
sveiciens = "Esi sveicināts!"
latvijas_regionu_skaits = 4
eur_to_usd = 1.02
```

#### Teksta mainīgie

```python
sveiciens = "Esi sveicināts!"
vards = "Toms"
print(sveiciens, vards) # Tiek drukāts "Esi sveicināts! Toms"
```

#### Būla mainīgie
```python
sveiciens = "Esi sveicināts!"
latvijas_regionu_skaits = 4
eur_to_usd = 1.02
```

### Konvertācija
Operācijas, kas ir iespējamas ar vienu datu tipu varētu būt neloģiskas un neiespējamas ar citu.


### 


## Nosacījumi (zarošana)


## Cikli

### For cikls

### While cikls



## Funkcijas


## Saraksti


## Vārdnīcas


## Objekta Orientēta Programmēšana (OOP)


