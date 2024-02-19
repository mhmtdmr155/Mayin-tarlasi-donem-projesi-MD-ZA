# Mayin-tarlasi-donem-projesi-MD-ZA
NxN boyutlarında bir oyun tahtasında, oyuncu ‘G’ noktasından ‘Ç’ noktasına ulaşmaya çalışmaktadır.
Tahtada rastgele konumlarda mayın bulunmaktadır. Amaç mayınlara basmadan ‘Ç’ noktasına varmak.
 Bir mayının bulunduğu kare ve o kareyi çevreleyen kareler (kuzey, güney, doğu ve batı
konumları) üzerine gelindiğinde de mayın patlamaktadır.
o Mayının üzerine gelindiyse oyuncu elenir, çevreleyen karelerden birine geldiyse devam
edebilir ancak ‘G’ noktasına geri döner.
 Oyuncu tahtada yön tuşları ile hareket eder.
 Alanın boyutu (yani n değeri) oyuncudan alınacaktır.
 Mayın sayısı alandaki toplam kare sayısının %10’u kadar olacaktır.
 Oyun başladığında;
o Mayınlar alana rastgele yerleştirilecektir. Oyuncu mayınların yerini bilemez, tahtada
göremez.
o Oyuncunun ilk konumu ‘G’ noktasıdır.
 Oyuncu çıkışa ulaştığında güvenli yolun tahta üzerinde çizilmesi gerekir. 
n değeri 10 verilmiştir. Yani mayınlı bölge 10x10 boyutlarındadır. (n değerini kullanıcıdan
almanız gerekmektedir.)
 10x10 luk bir matriste, toplam 10x10=100 kare bulunduğundan, mayın sayısı 100*0,1=10’dur.
 Alanda mayınlar ‘o’ ile temsil edilmiştir. (İstediğiniz başka bir sembol ile de mayınları temsil
edebilirsiniz.)
 Mayınlar karelere rastgele yerleştirilecektir. Rastgele konum üretildikten sonra, o konuma
daha önce mayın yerleştirilmiş mi kontrol edilmelidir.
Bir mayının üst, alt, sağ, sol kareleri o mayının etki alanıdır. Yani güvensiz bölgelerdir. Örnekte
mayını çevreleyen alanlar ‘x’ ile gösterilmiştir. (istediğiniz başka bir simge ile de
gösterebilirsiniz.)
 Örneğin yukardaki örnek için oyuncu çıkış noktasına ulaştığında oyun tahtasında geçtiği yol
aşağıdaki gibi işaretlenmelidir.
o Bunun için geçilen yerleri hafızada tutmanız gerek
o Çıkışa giden yol tek olmayabilir, boyanacak olan oyuncunun çıkışa gitmek için
kullandığı yol.

Alanda mayınları ve riskli bölgeleri temsil eden simgeleri kendinize göre tanımlayabilirsiniz.
Ancak tüm mayınlar için bir simge ve tüm riskli bölgeler için bir simge seçmelisiniz.
 Oyuncunun her adımı sonrası oyun tahtası ekrana basılmalıdır.
o Oyuncunun o an ki konumu da her adım sonrası tahtada gösterilmelidir.
o Oyuncuyu temsil etmek için de bir karakter kullanabilirsiniz.
 Kullanıcı bir mayın veya etki alanı olan bölgeye bastıysa o konumu kendisi aklında tutmalıdır,
tahtada bunu kullanıcıya hatırlatma amaçlı gösteren bir işaret olmayacaktır.
 Kullanıcı oyun tahtası dışına çıkamaz
o Kullanıcının hamlelerinin tahta içinde olup olmadığı kontrol edilmeli
 ‘G’ ve ‘Ç’ noktalarında mayın olamaz.
o Tahtaya mayınlar rastgele yerleştirilirken ilgili mayın için rastgele seçilen konumun bu
2 noktadan biri olup olmadığı kontrol edilmelidir.
 Bir mayının etki alanının (kuzey, güney, doğu ve batı) olduğu karelere;
o başka bir mayın yerleştirilebilir ancak 2 mayın üst üste gelemez.
o Bir mayının etki alanı olan ‘x’ noktaları da ‘G’ ve ‘Ç’ ile çakışamaz.
 Mayınları yerleştirirken bu kontrolün yapılması gerekir.
 Mayınlar rastgele yerleştirildiği için tahtada ‘G’ den ‘Ç’ye gidilebilecek bir yol olmayabilir. (Ç
noktası bir mayının etki alanı ile çevrelenmişse bu durum oluşacaktır.)
o Oyuncuya sunulacak menüde ‘oyun tahtasını yeniden konumlandır’ şeklinde bir
seçenek ile kullanıcıya restart yapması sağlanmalıdır.
o Yani oyuncu başa döner, tahtada tüm mayınlar yeniden konumlandırılır




ENGLİSH

A mine and its surrounding squares (north, south, east, and west) are considered dangerous.
Stepping on a mine eliminates the player. Stepping on a surrounding square returns the player to 'G'.
The player moves using arrow keys.
The grid size (n) is input by the player.
The number of mines is 10% of the total squares.
Mines are randomly placed and hidden from the player.
The player starts at 'G'.
A safe path is drawn on the board when the player reaches the exit.
Specifications:

n = 10 (user input)
Mine count = 100 * 0.1 = 10
Mines are represented by 'o'.
Affected areas are represented by 'x'.
The player's current position is shown on the board.
The player cannot move outside the board.
'G' and 'Ç' cannot be mine locations.
'x' cannot overlap with 'G', 'Ç', or other mines.
The game can be restarted if there is no path from 'G' to 'Ç'.
Additional Information:

The player keeps track of mined and affected squares mentally.
The menu includes a "reposition board" option for restarting.
Mines are randomly placed, so a path may not always exist.
Improvement Notes:

The game can be improved by adding a timer, score, and multiple difficulty levels.
Visual effects can be added for explosions and safe paths.
This game can be a fun and challenging way to practice your programming skills.

I hope this information is helpful.

Please let me know if you have any questions.
