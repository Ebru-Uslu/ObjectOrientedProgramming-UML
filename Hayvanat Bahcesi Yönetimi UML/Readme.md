# Hayvanat Bahçesi Yönetim Sistemi

Bu proje, bir hayvanat bahçesindeki farklı hayvan gruplarının bilgilerini takip etmek ve yönetmek amacıyla tasarlanmış bir sistemdir. Polimorfizm prensibini kullanarak, farklı hayvan grupları için özelleşmiş davranışlar sağlayan bir sınıf yapısı tasarlanmıştır.

## Özellikler

-Hayvanlar:

-Atlar (atlar, zebralar, eşekler vb.),

-Kedigiller (kaplanlar, aslanlar vb.),

-Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.

-Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.

-tür adı, ağırlığı, yaşı vb.

-Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()

-Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()


Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.


