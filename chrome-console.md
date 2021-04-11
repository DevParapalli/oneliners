# Chrome Console OneLiners

IBB Link Extractor
  - `l=""; document.querySelectorAll('.list-item').forEach((e)=>{ l+=JSON.parse(decodeURIComponent(e.dataset["object"]))["image"]["url"]+"\n"; }); copy(l);` 
