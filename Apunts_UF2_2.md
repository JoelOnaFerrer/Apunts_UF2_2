# APUNTS UF2_2
## Optimització
### Hediondez del codi
L’hediondez és qualsevol indicació de que el codi font té algun error profund. Normalment no son bugs del programa ja que no impideix que le programa funcioni correctament. Et diu les deficiencies del disseny que poden augmentar el risc d’errors.

Uns exemples d'hediondez poden ser:

    • Codi duplicat
    • Massa paràmetres
    • Herència rebutjada
    • Clases grans
    • Metòdes grans

## Anàlisi del Codi
Hi han dos tipus d'anàlisi que poden ser:

  - **Anàlisi dinàmic** : Que utilitzen el tipus de proves Junit.

  - **Anàlisi estàtic** : Utilitzen el tipus de proves de lint. Alguns analitzadors de codi poden ser:
    - **Lint** : Per al llenguatje de **C** .
    - **Sonar** : Per al llenguatje de **Java** .
    - **JSLint, ESLint** : Javascript

  També poden aver-hi llocs webs que poden analitzar estàticament el codi com:

   - **Scrutinizer**
   - **SonarQube**  

## Refactorització

És el procés de canviar la seva estructura intera sense canviar els seu compartament, com per exemple canviar el nom d'una variable o funció. Hi han varies tècniques:

- Renombrar variables
- Pasar codi duplicat a funcions
- Eliminació del codi inassolible
- Eliminació de codi repetit
- Eliminació de codi mort

## Documentació
Hi han tres tipus de documentació.

- **Documentació del codi** : És la documentació en el propi codi com per exemple a Java el JavaDoc.
- **Documentació tècnica** : És la documentació de la funcionalitat del programa dirigit a un públic avançat.
-  **Documentació d'usuari** : És la documentació bàsica per a l'usuari.

Hi han diversos formats de documentació com:
- **HTML** : Com per exemple el JavaDoc.
- **Markdown** : Com per exemple Github.
- **reStructuredText** : Com per exemple Readthedocs.
- **asciiDoc**
