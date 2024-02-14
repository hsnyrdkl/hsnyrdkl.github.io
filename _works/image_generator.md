---
title: "Image Generator"
subtitle: "2023"
thumbnail: "/images/openai.png"
---

**Platform** Web
**Stack \_Frontend** React, Next.js, Tailwind CSS
**Stack_Backend** Node, MongoDB, Express, Render, Cloudinary
**Demo** [Live](https://hasanimagegenerator.netlify.app/)
**Code** [Github](https://github.com/hsnyrdkl/image_generator_app)

Oluşturduğum platform, OpenAI API servisini kullanarak oluşturduğumuz fotoğrafları yönetmektedir. Kullanıcılar platform üzerinden fotoğraflar oluşturabilir, oluşturulan fotoğrafları görüntüleyebilir, paylaşabilir ve düzenleyebilirler. Frontend tarafında React ve Next.js kullanılarak güçlü bir kullanıcı deneyimi sunulurken, Tailwind CSS kullanılarak da kullanıcı arayüzü tasarlanmıştır.

Backend tarafında Express kullanarak API'ler oluşturulmuş ve MongoDB kullanılarak veritabanı işlemleri gerçekleştirilmiştir. Bu platform, kullanıcıların oluşturulan imajları paylaşabilecekleri ve bulut tabanlı depolama sağlayıcısı olan Cloudinary'de depolayabilecekleri bir arayüz sunar. Kullanıcılar, fotoğraflarını platformda paylaştıktan sonra, bu fotoğrafları Cloudinary bulutlarında güvenli bir şekilde saklayabilir. Oluşturduğum platformun serverları Render'da barındırmaktadır. Kullanıcıların fotoğraf oluşturma işlemlerini gerçekleştirdikten sonra, bu fotoğraflara ait datayı MongoDB veritabanında saklar. Server Render tarafından yönetildiği için platform hızlı ve güvenilirdir. Bu sayede, kullanıcılar platformu sorunsuz bir şekilde kullanabilir ve fotoğraflarını kolaylıkla yönetebilirler. Bu sayede, kullanıcıların fotoğraflarını güvenli bir şekilde yükleyebilmesi ve yönetebilmesi sağlanmıştır.

![1](https://hasancv.netlify.app/images/projeler/image_generator_1-min.png)

API Call yaptığımız sayfa. Bu sayfa üzerinden input field'a bir promp giriyoruz ve "Generate" butonuna basarak Open AI servislerinin bize fotoğrafı oluşturmasını bekliyoruz. Fotoğraf oluştuktan sonra "Submit" butonunu kullanarak, oluşturulan fotoğrafı platformda paylaşabiliriz.

![2](https://hasancv.netlify.app/images/projeler/image_generator_2-min.png)

Platformun anasayfası. Oluşturulan tüm fotoğraflar görüntülenebilir ve anahtar sözcüklere göre filtrelemesi yapılabilir.

![3](https://hasancv.netlify.app/images/projeler/image_generator_3-min.png)

Card component'ının üzerine imleç hover edildiğinde ortaya çıkan arayüzden, oluşturulan fotoğraflar Cloudinary serverlarından fetch edilerek png formatında cihaza kaydedilebilir.
