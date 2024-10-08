# Victor Nuñez

<h2 align="center">About me</h2>

```php
<?php
    class Biografia {
        public function main(){
            $bio = $this->getBio();
    
            foreach ($bio as $key => $item) {
                echo "$key : $item \t\n";
            }
        }

        public function getBio(){
            $bio = [
                "-⚡ Quick bio:" => "Soy una especie de bmx-monsteradicto-amantedelacomida-trap-rap-coder-programmer-amantedelosgatos.",
                "-🌱 Actualmente estoy aprendiendo:" => "Estoy estudiando Data Science, actualmente hago un Diplomado de Data Science en la USM (Universidad Técnica Federico Santa María)",
                "-🤔 Estoy buscando ayuda con" => "Cualquier cosa relacionada con lo que estoy aprendiendo actualmente 😅",
                "-💬 Pregúntame sobre" => "Python, PHP, Laravel, SQL, Diseño y arquitectura de software, Desarrollo web y SEO",
            ];  
            return $bio;
        }
    }

    $biografia = new Biografia();
    $biografia->main();
    
?>
```
```bat
PS C:\Users\Victor Nuñez\Desktop> php .\Biografia.php
-⚡ Quick bio: : Soy una especie de bmx-monsteradicto-amantedelacomida-trap-rap-coder-programmer-amantedelosgatos. 
-🌱 Actualmente estoy aprendiendo: : Estoy estudiando Data Science, actualmente hago un Diplomado de Data Science en la USM (Universidad Técnica Federico Santa María) 
-🤔 Estoy buscando ayuda con : Cualquier cosa relacionada con lo que estoy aprendiendo actualmente 😅 
-💬 Pregúntame sobre : Python, PHP, Laravel, SQL, Diseño y arquitectura de software, Desarrollo web y SEO 
```
![](http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Skeiceee&theme=dark)
![](http://github-profile-summary-cards.vercel.app/api/cards/stats?username=Skeiceee&theme=dark)
