---
layout: post
title:  "Jekyll Blog Oluşturma - 1"
permalink: "/eps1.0_hellofriend.mov/"
---

## _eps1.0_hellofriend.mov_

Merhaba, jekyll ile github üzerinde statik blog oluşturmayı öğretiyorum. Oldukça kullanışlı ve ücretsiz olmasından ötürü ben de kullanıyorum.

### Kurulum

Jekyll, `Ruby` tabanlı bir gem. Biz geliştirmeyi [github](github.com) üzerinde yapacağımız için yanına `github-pages` ve `bundle` adlı gemleri de kuracağız. Bilgisayarımıza kurmak için yüklü olması gereken paketler:

- Ruby
- Ruby Gems
- Bundler

Bu paketleri yükledikten sonra terminale

\# `gem install github-pages`

\# `gem install bundle`

yazarak kurulumu başlatabilirsiniz. 

***UYARI: root yetkisine sahip değilseniz komuta `--user` argümanını eklemeli ve `$PATH` değişkeninde ruby bin/ dizini olduğuna emin olmalısınız.***

### Template oluşturma

Projeyi oluşturmak istediğiniz dizine gidin ve aşağıdaki komut ile template dosyalarını oluşturun.

$`jekyll new myblog`

oluşan dosyalar bu şekile olmalıdır.

    - myblog            => Ana dizin
        - _posts        => Postların olduğu dizin
        - _config.yml   => Site değişkenlerinin bulunduğu config dosyası
        - Gemfile       => Gem bağımlılıklarının bulunduğu dosya
        - 404.html      => 404 not found sayfası
        - about.md      => about - örnek sayfa
        - index.md      => anasayfa


Bu şekilde kurduktan sonra düz html ve markdown kullanarak bile istediğinizi yaparsınız. Ancak yapmayın öyle bir şey :)

Bir sonraki yazıda postlarımızı oluşturup Anasayfada otomatik listeleyeceğiz. Görüşmek üzere...