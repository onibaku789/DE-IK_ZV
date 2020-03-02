## Lexikális egységek. Adattípusok. Nevesített konstans. Változó. Kifejezések. Utasítások.Programegységek. Paraméterkiértékelés, paraméterátadás. Blokk. Hatáskörkezelés, láthatóság. Absztrakt adattípus. Kivételkezelés.

# Infó2

- Lexikális egységek: Hat osztályba sorolhatóak: Azononsítók, kulcsszavak, állandók, karakterláncok, operátorok és egyéb szeparátorok. A szóközötket, tabulátorokat, újsorokat, megjegyzések(közös nevükön üres helyek) a fordító nem veszi figyelembe.
  - Megjegyzések: A /\* karakterek megjegyzést vezetnek be , amely a \*/ karakterrel zárul.
  - Azonosítók: Az azonosítók a beűk és számjegyek sorozata; az első karakter betű kell, hogy legyen, A aláhúzásjel betűnek számít, A nagy és kisbetűk különbözőek.
  - Kulcsszavak: Az alábbi azonosítók a nyelv kucsszavai, így egyéb célra nem használhatók: int else for …..
  - Állandók: Többfajta állandó van.
    - Egész állandók: A számjegyek sorozatát tartalmazó egész típusú (integer) állandót a fordító oktálisnak tekinti, ha 0-val (a nulla számjeggyel) kezdődik, egyébként decimálisnak veszi. A 8 és 9 számjegyek oktális értéke 10, ill. 11 . Az olyan számjegysorozatot, amelyet 0X vagy 0x (a 0 a nulla számjegy) előz meg, a fordítóprogram hexadecimális egésznek tekinti. Hexadecimális számjegyek az a-tól, ill. A-tól f-ig, ill. F-ig elhelyezkedő karakterek, amelyeknek értéke 10, . . ., 15. Azt a decimális állandót, amelynek értéke meghaladja a gépen ábrázolható legnagyobb előjeles egészt, a fordítóprogram long-nak veszi; hasonlóképpen long lesz az az oktális vagy hexadecimális állandó, amelynek értéke meghaladja a legnagyobb, elôjel nélküli gépi egészt.
    - Explicit long állandók: Az a decimális, oktális vagy hexadecimális egész, amelyet közvetlenül l („el&quot; betű) vagy L követ, long (hosszú) állandó. Amint arról az alábbiakban szó lesz, bizonyos gépeken az int és long értékek azonosak.
    - Lebegőpontos állandók: A lebegőpontos állandó egész részből, tizedespontból, törtrészből, e-ből vagy E-bôl és (esetleg előjeles) kitevőből áll. Mind az egész, mind a tört rész számjegyek sorozata. Akár az egész, akár a tört rész hiányozhat (de mind a kettő nem!); ill. a tizedespont vagy az e és a kitevő közül az egyik szintén elmaradhat. Minden lebegőpontos állandó duplapontosságú.
  - Karakterláncok: A karakterlánc idézőjelek közé zárt karaktersorozat: &quot;….&quot;. A karakterlánc típusa szerint karaktertömb, tárolási osztálya static, és a megadott karakterek inicializálják. Az egyes karakterláncok, még az azonos módon leírtak is, külön egységet képeznek. A fordító minden karakterlánc végére elhelyezi a \0 nullabyte-ot abból a célból, hogy a karakterláncot vizsgáló programok megtalálják a karakterlánc végét. A karakterláncon belül elhelyezett „ idézôjelet \ kell, hogy megelôzze; a karakterállandóknál ismertetett összes escape-szekvencia használható. Végül megjegyezzük, hogy az \-t és az azt közvetlenül követô újsort a fordító nem veszi figyelembe
  - Operátorok:
  - Szeparátorok:





- Adattípusok: A programok alapvető adatobjektumai a változók és az állandók. A deklarációk felsorollják a használni kívánt változókat, közlik a típusukat, valamint az esetleges kezdeti értéküket.
- Nevesített konstans: Egy nevesített konstansnak három komponense van (típus, név, érték). Muszáj mindig deklarálni. Egy nevesített konstans a neve álltalál van reprezentálva a forráskódban. A név mindig egy érték kompononenst takar. Az érték komponenst nem lehet változtatni futási időben, a deklarálásnál eldőlt az értéke. A nevesített konstant szerepe az, hogy engedjük a programozót, egy gyakran használt értéknek egy jól leíró nevet adni. Az előnye, hogy elegendő a deklarálásnál megváltoztatni az értékét, nem kell az összes előfordulásánál változtatni.
- Változó.
- Kifejezések: A kifejezések a változókból és állandókból új értéket hoznak létre.
- Utasítások.
- Programegységek.
- Paraméterkiértékelés, paraméterátadás.
-
- Hatáskörkezelés, láthatóság.
- Absztrakt adattípus.
- Kivételkezelés.