[<- Tilbake til innholdsfortegnelsen](https://github.com/amundsor/ntnu_xsessions/blob/master/README.md)
# 5. Kodekvalitet
### SOLID-prinsipper, Clean Code, etc, etc.
* Er som regel en forventning (på generelt grunnlag)
* Ha et bevisst forhold til kodekvalitet
* Tilstreb "selvforklarende" kode

### Yrkesstolthet

"_Stolthet som man føler som utøver av et bestemt fag, yrke, 
især knyttet til god og korrekt utøvelse_"

* Skriver du en stil, leverer du aldri (sjelden) førsteutkastet
* KISS: Min kode skal forvaltes av andre
* Forlat kode i bedre stand enn du fant den

````java
// NOT!!!!!
class RelRgCars {
    private String regnr;
    private CMdl cMdl;
    private String com;
}
// BETTER
class RelevantRegisteredCars {
    private String registrationNumber;
    private CarModel model;
    private String countryOfManufacturing;
}
````

- [Neste -> Jobbsøknad](https://github.com/amundsor/ntnu_xsessions/blob/master/src/main/java/no/amundsor/xsessions/6_jobb.md)