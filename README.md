<!---
MediumDubb/MediumDubb is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<?php 
  namespace Bio\Author\NoahWhittington
  
  use Bio\Vendor\PHP
  use Bio\Vendor\HTML
  use Bio\Vendor\CSS_SCSS
  use Bio\Vendor\JS
  use Bio\Vendor\SilverStripe_CMS
  use Bio\Vendor\Wordpress(AKA TurdPress)
  use Bio\Author\BaseDescription 

  class NoahWhittington extends BaseDescription
  {
    private static $interests = [
      "Sports"      => ["Golf", "Skiing", "Running"],
      "Nerdish"     => ["Anime", "Gaming, Future Funk", "Organizing Information", "Cars"],
      "Learning"    => ["Better JS Practices", "Rendering Complex Animation", "PHP Class Reflection"],
      "Religious"   => [true, "Jesus is Lord"],
    ]

    public function tooLazy2Finsh(){
      return "2 LaZy 2 FiNiSh tHiS!";
    };
  }
