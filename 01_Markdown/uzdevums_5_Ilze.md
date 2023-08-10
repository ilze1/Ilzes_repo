### Darbs ar Git

**1. Mapē git_repos noklonēt**  https://github.com/hashicorp/terraform **projektu**

Izmantotā komanda: 

git clone git@github.com:hashicorp/terraform.git

**2. Pārbaudīt kādas izmaiņas tika veiktas iepriekšējās nedēļas laikā. Atrast vismaz divus veidus kā to izdarīt.**

Iepriekšējā nedēļā no 31.jūlija līdz 6. augustam tika veiktas izmaiņas, kuras iespējams atlastīt šādi: 
* git log --since="2023-07-31" --before="2023-08-06" 
* git log --since=2.weeks --until="2023-08-06"

**3. Atrast commit kurus veica autors  - “Laura Pacilio”**

Lauras veiktie commiti:

git log --author='Laura Pacilio'

**4. Atrast vai Laura ir veikusi commit pagājušā gada septembrī?**

Jā, ir veikusi!

git log --author='Laura Pacilio' --after="2022-08-31" --before="2022-10-01"

**5. Vai Laura ir veikusi commit vakar?** 

Nē, nav veikusi!

git log --author='Laura Pacilio' --since=yesterday

**6. Rezultatus apkopot MD faila** 

MD rezultātu datne pieejama [šeit](https://github.com/ilze1/ilzes_repo/tree/main/01_Markdown). 
