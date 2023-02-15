# Domácí úkol &mdash; podmínky, cykly, switch

Zápis cyklů a&nbsp;podmínek si procvičíš na projektu, kde požádáme uživatele o&nbsp;zadávání čísel z&nbsp;klávesnice a&nbsp;takto zadaná čísla budeme zpracovávat.

Tvým úkolem je dopsat těla (kód) metod podle popisu v&nbsp;komentářích.

Protože čtení z&nbsp;klávesnice zatím neumíme, připravili jsme ti třídu `Support` s&nbsp;metodou `Support.safeReadInt()`, která načte z&nbsp;klávesnice jedno číslo a&nbsp;vrátí ho jako návratovou hodnotu. V&nbsp;úlohách můžeš tuto metodu využít.


## Postup stažení šablony projektu

Doporučujeme otevřít projekt z&nbsp;repozitáře:
1. Otevři IntelliJ IDEA (případně zavři otevřený projekt pomocí _File &rarr; Close_).
2. Zvol _Get from VCS_:  
    ![Při otevření IDEI na úvodní obrazovce zvol "Get from VCS"...](img/git_open-repo_02_get-from-vcs.png)
3. Zadej adresu tohoto repozitáře:<br />`git@github.com:ENGETO-Java-Akademie-2022-07/du-lekce-03.git`<br />
    Adresu repozitáře najdeš také na GitHubu:  
    ![Adresu repozitáře najdeš také na GitHubu:](img/git_open-repo_01_get-link.png)  
4. Naklonuj repozitář:  
    Do kolonky "Directory" zapiš cestu k&nbsp;adresáři, kde máš své projekty.  
    _(Obvykle by ji IntelliJ mělo vyplnit samo podle předchozího nastavení.)_  
    ![Naklonuj repozitář](img/git_open-repo_03_clone-repo.png)
5. Abys mohl(a) později projekt publikovat, musíš nastavit, že projektu důvěřuješ:  
   ![Zvol _Důvěřovat projektu_ (_Trust project_)](img/git-idea_02-clone_040-trust.png)
5. Najdi si třídu `Main`. IDEA tě požádá o nastavení SDK:  
    _(Nabízené SDK se můžou u tebe lišit od obrázku podle toho, jaké máš nainstalovány.)_  
    ![Najdi si třídu `Main`. IDEA bude chtít nastavit SDK](img/git_open-repo_04_main-and-sdk.png)
6. Nyní již můžeš psát kód a spouštět ho.  
    ![Spuštění programu](img/git_open-repo_05_run.png)

PS: Takto si můžeš otevřít jakýkoli repozitář z&nbsp;GitHubu.

Nebo si prostě stáhni projekt ručně: 
- vytvoř svůj projekt s&nbsp;balíčkem (package) `com.engeto.ifloop`
- zkopíruj do něj obsah souborů:<br />
[Support.java](src/com/engeto/ifloop/Support.java)
<br />a&nbsp;[Main.java](src/com/engeto/ifloop/Main.java)
- případně oprav název balíčku na prvním řádku tak, aby odpovídal tvému projektu.

## Zadání

- Doplň těla všech metod podle popisu v&nbsp;komentářích.

- Ve výsledku by každá metoda měla plnit to, co je popsáno v&nbsp;jejím komentáři.

- Metody mají číst vstup z&nbsp;klávesnice. Ten budeš zadávat do okna spuštěné aplikace:<br />
        ![Zadání vstupu z&nbsp;klávesnice](img/git_open-repo_06_enter-keyboard.png)<br />
        ![Výsledek demo kódu před řešením prvních úkolů](img/git_open-repo_07_demo.png)

## Obtížnější části &mdash; na co si dát pozor!
1. V&nbsp;listu by nemělo být uloženo záporné číslo, kterým jsme ukončili vstup.


## Publikování projektu

Až budeš hotov, můžeš projekt publikovat.
1. Nejprve musíš zvolit _Trust project_, pokud jsi tak už neučinil(a) při klonování. Jinak není práce s&nbsp;Gitem povolena.
   ![Zvol _Trust project_, pokud jsi to už neprovedl(a) při klonování](img/git-idea_02-clone_045-trust-later.png)  
   ![Potvrď nastavení důvěryhodnosti...](img/git-idea_02-clone_047-trust-later-2.png)
2. Nyní už stačí publikovat projekt stejně jako každý jiný.  
   ![_Git &rarr; Share on GitHub_](img/git-idea_02-clone_060-publish.png)  
   ![](img/git-idea_02-clone_070-share.png)  
3. Navíc musíš potvrdit, že chceš změnit vzdálený repozitář.
   ![Potvrď _Share anyway_](img/git-idea_02-clone_070-share-anyway.png)
   ![IDEA by měla zobrazit bublinu, že klonování proběhlo v&nbsp;pořádku](img/git-idea_02-clone_080-success.png)
4. Nyní už můžeš provádět _commit_ a _push_ stejně jako v&nbsp;ostatních projektech.  
   ![Přidej soubory do commitu a napiš commit message](img/git-idea_01-new-prj_200-next-commit.png)  
   ![Odešli commity příkazem _push_](img/git-idea_01-new-prj_210-push.png)

---
