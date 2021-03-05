
<p align="center">
<img height="50"src="https://raw.githubusercontent.com/sidbelbase/sidbelbase/master/wave.gif"/> <samp style="font-size:40px;">Hey!</samp>
</p>

 </br>
<p align="center">
<samp>
I'm Isaac. A passionate software programmer, eager to learn something new each day :D
</samp>
</br></br>

```js
import SoftwareDeveloper from 'myData';

class Bio extends SoftwareDeveloper {
  name     = 'Isaac Maldonado';
  title    = 'In progress...';
  location = 'Guatemala, Guatemala';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript','Java','Typescript', 'C','C++','C#','Python','Assembly','Dart','Go'];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL','Oracle'];
  frameworks = ['Angular','Flutter','Bootstrap'];
  libraries  = ['React']
}
```

</p>
<samp>
<p align="center">
<a href="www.linkedin.com/in/isaac-maldonado-4745b2194">Linkedin</a> | <a href="https://twitter.com/Anaklusmos99">Twitter</a>
</p>

<h2 align="center"><samp>Github Stats</samp></h2>

<a href="https://github.com/paulj1989/github-readme-stats">
  <img align="center" src="https://github-stats-51zyiojh0.vercel.app/api?username=einjunge99&&how_icons=false&count_private=true" />
</a>
<a href="https://github.com/github-readme-stats">
  <img align="center" src="https://github-stats-51zyiojh0.vercel.app/api/top-langs/?username=einjunge99&&layout=compact" />
</a>


<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->

------

Last Edited on: 05/03/2021

