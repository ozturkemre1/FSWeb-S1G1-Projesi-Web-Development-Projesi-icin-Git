# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

    Git, Open Source Distributed Version Control System'dir. Kodu geliştirirken versiyonları kayıt altında tutar.

2. Git ile GitHub arasında ne fark var?

    Git verileri kayıt altında tutma işlemidir. Github ise bu Git'leri bulut tabanında barındırır.

3. Neden bir branch oluşturuyoruz?

    Çünkü kod geliştirilirken istediğimiz bölümü ana koda zarar vermeden değiştirip entegre etmek daha sağlıklıdır. Bu yüzden Branch kullanırız.

4. Pull Request'in amacı nedir?

    Pull Request yöneticiye projede revize yapıldığını ve onaylanıp ana koda eklenmesi istendiğinde oluşturulan taleptir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

    Git checkout komutuyla branchler arası geçiş yapılır. git checkout master diyerek ana branche geçiş yapabiliriz.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

    git fetch lokal repoyu remote'a günceller, git pull remote repo'yu lokal'e günceller. git merge ise yeni açılan branchi ana branche bağlamaya yarar.

7. Merge conflict nedir?

    İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?

    Projeyi yönetenler ile görüşüp ortak bir payda bulunması gerekir.
