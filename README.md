# Հոդվածների որոնման հավելված

Այս հավելվածը նախատեսված է հոդվածների որոնման, դիտման, հիմնական կետերի առանձնացման և տեքստում տերմինների բացատրության համար։ Այն ներառում է մուտքագրման, որոնման, API բանալու կառավարման և ելքի գործառույթներ։

[Դեմո տարբերակ](https://lorsabyan.github.io/vaf-bg-article-explorer/)

## Հիմնական գործառույթներ

- **Մուտք համակարգ**  
  Օգտագործողները կարող են մուտք գործել իրենց էլ. փոստի և գաղտնաբառի միջոցով։

- **Հոդվածների որոնում**  
  Հնարավորություն է տրվում որոնել հոդվածներ ըստ տեքստի և դիտել արդյունքները։

- **Հոդվածի բովանդակության դիտում**  
  Ընտրված հոդվածի բովանդակությունը ցուցադրվում է հիմնական տարածքում։

- **Տերմինների բացատրություն**  
  Հոդվածի տեքստում որևէ բառ կամ արտահայտություն ընտրելիս՝ ստանալ դրա բացատրությունը Gemini API-ի միջոցով։

- **Հիմնական կետերի առանձնացում**  
  Հոդվածի հիմնական կետերը կարելի է առանձնացնել և դիտել մոդալ պատուհանում։

- **Gemini API բանալու կառավարում**  
  Օգտագործողները կարող են պահպանել կամ մաքրել իրենց Gemini API բանալին։

- **Ելք համակարգից**  
  Օգտատերերը կարող են դուրս գալ իրենց հաշվից։

## Տեխնիկական մանրամասներ

- **HTML և CSS**  
  Օգտագործվում է TailwindCSS և Google Fonts (`Inter`)՝ դիզայնի համար։

- **JavaScript**  
  Հավելվածի ինտերակտիվությունը ապահովվում է JavaScript-ի միջոցով։

- **API ինտեգրում**  
  Հավելվածը ինտեգրվում է հետևյալ API-ների հետ.
  - Identity API (`https://identity.api.bg.cluster.vecto.digital/api`)
  - Indexing API (`https://indexing.api.bg.cluster.vecto.digital/api`)
  - Gemini API (`https://generativelanguage.googleapis.com`)

## Օգտագործման ուղեցույց

1.  **Մուտք գործել**  
    Մուտքագրեք ձեր էլ. փոստը և գաղտնաբառը, ապա սեղմեք "Մուտք գործել" կոճակը։

2.  **API բանալու կառավարում (ըստ անհրաժեշտության)**  
    - Սեղմեք Gemini API բանալու պատկերակը վերևի վահանակում՝ բանալու դաշտը բացելու համար։
    - Մուտքագրեք ձեր API բանալին և սեղմեք "Պահպանել"։ Սա անհրաժեշտ է տերմինների բացատրության և հիմնական կետերի առանձնացման համար։

3.  **Հոդվածների որոնում**  
    - Մուտքագրեք որոնման բառը ձախ վահանակում։
    - Սեղմեք "Որոնել" կոճակը՝ արդյունքները ցուցադրելու համար։

4.  **Հոդվածի բովանդակության դիտում**  
    - Սեղմեք ցանկալի հոդվածի վրա որոնման արդյունքների ցանկից՝ բովանդակությունը դիտելու համար։

5.  **Տերմինի բացատրության ստացում**  
    - Հոդվածը դիտելիս, նշեք (select) որևէ բառ կամ արտահայտություն տեքստում։
    - Եթե Gemini API բանալին մուտքագրված է, բացատրությունը կհայտնվի փոքրիկ պատուհանում (tooltip)։

6.  **Հիմնական կետերի առանձնացում**  
    - Հոդվածը դիտելիս, սեղմեք "Հիմնական կետեր" կոճակը (հոդվածի վերնագրի մոտ)՝ հոդվածի հիմնական կետերը դիտելու համար։

7.  **Ելք գործել**  
    - Սեղմեք "Ելք" կոճակը վերևի վահանակում՝ համակարգից դուրս գալու համար։

## Տեղեկություններ

- **Տվյալների պահպանում**  
  Մուտքի թոքենը (`accessToken`) և Gemini API բանալին պահպանվում են զննարկչի `localStorage`-ում։

- **Հավելվածի լեզու**  
  Հավելվածը նախատեսված է հայերեն լեզվով օգտագործման համար։

## Պահանջներ

- Զննարկիչ՝ JavaScript-ի աջակցությամբ։
- Gemini API բանալի՝ հիմնական կետերի առանձնացման և բացատրությունների համար։

## Նախագծի նպատակը

Այս հավելվածը ստեղծվել է հոդվածների որոնման և կառավարման գործընթացը հեշտացնելու համար։
