# Codice Fiscale
![Go](https://github.com/deeper-x/codice-fiscale/workflows/Go/badge.svg)

Sistema di generazione codice fiscale, a partire da:

```
name string
surname string 
birthCity string 
birthDate string 
gender string
```

Metodi esposti:

#### Genera codice fiscale
```
p := NewPerson("Mario", "Rossi", "Roma", "29/09/1936", "M")
fc, err := p.DoRequest()
...
```

#### Controlla codice fiscale
```
fc := "BRLSLV36P29F205X"
ok, err := p.Verify(fc)
...
```


