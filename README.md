### Easily Add Control Buttons for Leaflet

Relevant documentation and implementation in the [Demo][].

Changes from the original:
  * The Name
    * now: `L.Control.EasyButton ` (no trailing 's')
    * was: `L.Control.EasyButtons` (trailing 's')
  * function signature
    * now:
      * `<icon:string>`,`<callback:function>`
      * `<options:object>`
    * was:
      * `<icon:string>`,`<callback:function>`,`<map:leaflet-map>`,`<button-title:string>`,`<button-id:string>`

  * added features

## hey

if you use html for your icon, L.easyButton won't try to overwrite it;
`id` will be ignored. `title` will still work
[Demo]:http://cliffcloud.github.io/Leaflet.EasyButton/
