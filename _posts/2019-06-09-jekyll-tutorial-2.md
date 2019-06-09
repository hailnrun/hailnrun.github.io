---
layout: post
title:  "Jekyll Blog Oluşturma - 2"
permalink: "/eps1.1_ones-and-zer0es.mpeg/"
---

## _eps1.1_ones-and-zer0es.mpeg_

serimizin 2. ve son postu ile devam edelim. Bu sefer oluşturduğumuz blog'a post ekleyeceğiz ve ana sayfada sıralayacağız. 

### Post oluşturma

Post dosyaları `_posts` dizini altında bulunmalıdır. Öyleyse bu dizini oluşturun. Şimdi sırada dosyayı oluşturmak var. Postların dosya ismi aşağıdaki yapıda olmalıdır.
```ruby
YIL-AY-GUN-BASLIK.MD
```

ben dosyamın adını `2019-06-09-hello-world.md` olarak belirtiyorum ve içine

```markdown
---
layout: post
title:  "hello world!"
---

sayfa içeriği

```
yazıyorum. Bu işlemden sonra anasayfanıza gittiğinizde post un orada listelendiğini görebilirsiniz. Eğer listelenmediyse index.md dosyanıza gidip 

<pre>
&#x3C;&#x75;&#x6C;&#x3E;&#xA;&#x20;&#x20;&#x7B;&#x25;&#x20;&#x66;&#x6F;&#x72;&#x20;&#x70;&#x6F;&#x73;&#x74;&#x20;&#x69;&#x6E;&#x20;&#x73;&#x69;&#x74;&#x65;&#x2E;&#x70;&#x6F;&#x73;&#x74;&#x73;&#x20;&#x25;&#x7D;&#xA;&#x20;&#x20;&#x20;&#x20;&#x3C;&#x6C;&#x69;&#x3E;&#xA;&#x20;&#x20;&#x20;&#x20;&#x20;&#x20;&#x3C;&#x61;&#x20;&#x68;&#x72;&#x65;&#x66;&#x3D;&#x22;&#x7B;&#x7B;&#x20;&#x70;&#x6F;&#x73;&#x74;&#x2E;&#x75;&#x72;&#x6C;&#x20;&#x7D;&#x7D;&#x22;&#x3E;&#x7B;&#x7B;&#x20;&#x70;&#x6F;&#x73;&#x74;&#x2E;&#x74;&#x69;&#x74;&#x6C;&#x65;&#x20;&#x7D;&#x7D;&#x3C;&#x2F;&#x61;&#x3E;&#xA;&#x20;&#x20;&#x20;&#x20;&#x3C;&#x2F;&#x6C;&#x69;&#x3E;&#xA;&#x20;&#x20;&#x7B;&#x25;&#x20;&#x65;&#x6E;&#x64;&#x66;&#x6F;&#x72;&#x20;&#x25;&#x7D;&#xA;&#x3C;&#x2F;&#x75;&#x6C;&#x3E;&#xA;
</pre>

yazarsanız işlem tamamlanmış olur. Jekyll hakkında anlatacaklarım bu kadar. Bir sonraki yazıda görüşmek üzere...