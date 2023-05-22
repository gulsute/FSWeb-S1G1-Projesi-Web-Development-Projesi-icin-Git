Benim adım gülsu.


# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Açık kodlu yazılımların düzenlenmesi veya geliştirilmesi sürecinde yapılan değişikliklerin ve tüm versiyonların kaydedildiği, kronolojik olarak hem merkezi bir sunucuda hem de yazılımcının kendi bilgisayarında depolamasını sağlayan bir sistemdir.

2. Git ile GitHub arasında ne fark var?

Github, git depolama hizmeti sağlayan bir şirkettir. 

3. Neden bir branch oluşturuyoruz?

Yazılan kod üzerinde kalıcı bir değişiklik yapmak yerine yeni bir branchte bu değişiklikleri yapıp emin olduktan sonra ana branche bu düzenlemeler taşınabilir. Aynı anda birkaç kişinin aynı kod üzerinde çalışmasına imkan sağlayabilmek için. Ana amacı çalışan ilk kodu korumak.

4. Pull Request'in amacı nedir?

Değişiklik amacıyla aldığımız kodun tüm kopyalarıyla birlikte ana verisini değiştirmek için kullanırız.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

$ git switch main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

git fetch komutu farklı bir depolama alanından yerel depolama alanına kodu almamızı sağlar.
git merge komutu mevcut kodumuzla 1 veya daha fazla kodu birleştirmek için kullanılır
git pull fetch+merge olarak özetlenebilir, aldığımız kodu direkt olarak mevcut kodumuzla birleştirir.

7. Merge conflict nedir?

2 veya daha fazla kodu birleştirirken farklı kodlardaki aynı satırlarda değişiklik yapıldıysa veya birinde değişiklik yapılan satır diğerinde silindiyse oluşan bir hatadır. 

8. Merge conflict'i nasıl çözeriz?

oluşan conflicti anlamak için "status" ile öncelikle hangi dosyaların bu conflictten etkilendiğine bakarız. bu etkilenen dosyanın içinde hangi satır veya satırlarda problem olduğunu buluruz. yapılan değişikliklerden hangisinin kalacağına karar vererek gerekli düzenlemeyi yaparız. sonrasında dosyamızı açıklayıcı notumuzla birlikte yeniden yükleriz.
