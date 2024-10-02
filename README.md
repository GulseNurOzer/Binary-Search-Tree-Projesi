# Binary Search Tree (BST)

**Açıklama:**

Binary Search Tree (BST), her düğümün en fazla iki çocuğa sahip olduğu, düğümlerin belirli bir sırada düzenlendiği hiyerarşik bir veri yapısıdır. Bir düğümün sol alt ağacındaki tüm düğümler, düğümün değerinden küçük, sağ alt ağacındaki tüm düğümler ise düğümün değerinden büyüktür.

**Özellikler:**

* Her düğüm en fazla iki çocuğa sahiptir: sol çocuk ve sağ çocuk.
* Sol alt ağaçtaki tüm düğümler, düğümün değerinden küçüktür.
* Sağ alt ağaçtaki tüm düğümler, düğümün değerinden büyüktür.
* Verimli arama, ekleme ve silme işlemleri sağlar.

**Zaman Karmaşıklığı:**

* Arama, ekleme ve silme işlemleri için ortalama zaman karmaşıklığı: O(log n)
* En kötü durumda zaman karmaşıklığı (eğer ağaç dengesiz ise): O(n)
