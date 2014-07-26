divxplanet simple api

## Install

```
npm install divx
```

## Usage


```js
var divx = require('divx');

```

Example

```js
divx('V For Vendetta').then(function (data) {
	console.log(data);
}).catch(function(err) {
	console.log(err);
})

```

```json
{ writers: 
   [ { name: 'Andy Wachowski' },
     { name: 'Larry Wachowski' },
     { name: 'David Lloyd' } ],
  actor: 
   [ { name: 'Natalie Portman' },
     { name: 'Hugo Weaving' },
     { name: 'Stephen Rea' },
     { name: 'Stephen Fry' },
     { name: 'John Hurt' },
     { name: 'Tim Pigott-Smith' },
     { name: 'Rupert Graves' },
     { name: 'Roger Allam' },
     { name: 'Ben Miles' },
     { name: 'Sin&#233;ad Cusack' },
     { name: 'Natasha Wightman' },
     { name: 'John Standing' },
     { name: 'Eddie Marsan' },
     { name: 'Clive Ashborn' },
     { name: 'Emma Field-Rayner' } ],
  types: 
   [ { name: 'Aksiyon' },
     { name: 'Bilim-Kurgu' },
     { name: 'Gerilim' } ],
  comment: 
   [ { comment: 'bu filmin çok adını duydum çok övmüşlerdi bana.izledim pek beğenmedim belki de çok şey beklediğimden olabilir.yine de güzel film ama çok da abartılacak kadar değil.en güzel tarafı bi mantığı var filmin her düşünce oturtulmuş mantığa uygun yani.' },
     { comment: 'mükemmel bir film, sadece diyaloglar değil baştan aşağı sanat yapıtı... ama bu filmi kavramak için biraz birikim gereklidir...herkese hitap etmemesi de bu yüzdendir.' },
     { comment: 'Filmi beğendim..!!  izlerken farklı düşünceleri kafanızda olgunlaştırabilecek bir yapıyla sunmuşlar. Hitler Almanya\'sının gelişiminin gelecekte nasıl olabileceği ve uygulanabileceğini, korku senaryolarıyla toplumun nasıl sindirilebileceğini, bir fikrin yeşermesi, büyümesi ve ölümsüz olabilmesi için gerekli evreleri iyi anlattıklarını düşünüyorum.. ' },
     { comment: 'Kurgusu , senaryosu , V\'ye giydirilen gizem ve asalet.diyaloglarmükemmel , mükemmel' },
     { comment: 'Bu filmi öyle 2 cümleylen anlatılacak bişey değil gerçekten tam bir başyapıt...' },
     { comment: 'filmi anlamak için bilgi birikiminin olması gerektiğini sölemiş SLY kesinlikle katılıyorum ayrıca onun yanında da insanların duygu ve düşüncelerinin nasıl bastırılmış bir hal aldığı, devletin mi toplum için yoksa toplumun mu devlet için var olduğunu ve totaliter rejimlerim insanlığın karşısında eğilmeye mahkum olduğunu ve daha aklıma gelipte buraya yazarsam çok uzun olacanı düşündüğüm için yazmadığım daha nice neden...ama forum dan filmin incelemesi kısmını okursanız belki faydalı olur..kişisel görüşüm..kesinlikle izlenmesini istediğim dünya genelinde de esaretin bedeli ile birinciliği paylaşması gerektiğini düşüntüğüm bir başyapıttır..' },
     { comment: 'Kesinlikle izlenmesi gereken bir eser.. İngilizcesi iyi kişiler mutlaka orijinal dilinde seyretmeliler..' },
     { comment: 'Son zamanlarda sosyal mesajı vermenin bir üst levelini görebileceğiniz türden bir film.' },
     { comment: 'Kesinlikle İzlediğim En İyi Senaryoya Sahip Filmlerden Biri.Sanırım 4 Kere İzledim Ama Her İzlediğimde Yepyeni Şeyler Görüyorum Anlıyorum.Bağımsızlığımıza,Özgürlüğümüze Düşkün İsek Nasıl Bir Düşünce Yapısına Sahip Olmamız Gerektiğini Anlatıyor.En Önemlisi Özgürlüğün Vazgeçilmez Olduğunu Ve Bir Fikrin Gücünün Ne Kadar Sonsuz Olduğunu Bir Kez Daha Hatırlatıyor!' },
     { comment: 'abartılmayan, üst düzey film... kasımda v for vendetta başkadır :)\'\'Vi Veri Veniversum Vivus Vici\'\'' } ],
  desc: 'Korkunç yüzünü bir maskenin ardında gizleyen bu gizemli adam kim? Kahraman mı yoksa sadece çılgının biri mi? Liberal mi yoksa diktatör mü? V kimdir - ve totaliter rejime boyun eğen ulusunu bu çıkmazdan kurtarmak için ona kim yardım edecektir?<br><br>V For Vendetta , Matrix üçlemesinin yaratıcılarından geleceğin suç ve devrim dolu dünyasını gözler önüne seren ve aynı adlı çizgi romandan uyarlanan unutulmaz bir film. Natali Portaman, kahramanının verdiği savaşın toplum için bir tehdit olup olmadığına karar vermek zorunda olan Evey rolüyde göz dolduruyor. Hugo Weaving, V rolüyle cesur, karizmatik ve ona yapılan kötülüklerin intikamını almaya kararlı olan özgürlük savaşçısı olarak akıllardan silinmeyecek bir performans sergiliyor. Stephen Rea, devrimin alevini yakmadan önce V\'yi yakalamaya çalışan umutsuz bir dedektif. Tansiyon yükseliyor. Peki siz hangi taraftasınız? Unutmayın V\'nin dünyasında bir tarafı seçmek zorundasınız.',
  director: 'James McTeigue' }


```

