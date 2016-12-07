# Mininum
Custom keyboard (Numpad)
##The idea
The idea is to make a minimalistic numpad that you can carry with you anywhere, mainly for people taking their keyboards to/from work every day. In addition to that the minimum form factor is decided to fit the Planck made by Jack Humbert over at [OLKB](http://olkb.com), as that is my current favorite keyboard.

##Dimensions
- Height: 14mm (Case only, without silicon feet)
- Length: 81mm
- Width: 81mm
- Holes: 14\*14mm (Cherry MX compatible)

##Controller and firmware
The Mininum will use the QMK or TMK firmware flashed onto a microcontroller. The plan is program a layout according to the layout below to start with. The code will be in this repo.

The controller itself will be either a teensy 2.0 or some kind of arduino clone, and it will be handwired.

##Layout
* The [layout](http://www.keyboard-layout-editor.com/##@_name=Mininum&author=Wholteza&notes=%23%23%23%23INFO%0A*%20Layout%2F:%0A%20%20%20%20*%20Middle%20text%20%2F=%20Standard%20layer%20(NUMLOCK%20ON)%0A%20%20%20%20*%20Upper%20text%20%20%2F=%20Function%20layer%0A%20%20%20%20*%20Lower%20text%20%20%2F=%20Standard%20layer%20(NUMLOCK%20OFF)%0A%20%20%20%20*%20No%20text%20some%20of%20the%20layers%20%2F=%20Transparent%20key%20(Same%20as%20standard%20layer)%0A%20%20%20%20%0A%23%23%23%23Hardware%20license%20agreement%2F:%0A%0ACopyright%20(c)%202016,%20Wholteza,%20All%20rights%20reserved.%0A%0AThe%20copyright%20holders%20hereby%20grant%20to%20any%20person%20obtaining%20a%20copy%20of%20this%20design%20(the%20%22Open%20Design%22)%20and%2F%2For%20associated%20%0Adocumentation%20files%20(Documentation),%20the%20perpetual,%20irrevocable%20(except%20in%20the%20case%20of%20breach%20of%20this%20license),%20no-cost,%20%0Aroyalty%20free,%20sublicensable%20rights%20to%20use,%20copy,%20modify,%20merge,%20publish,%20display,%20publicly%20perform,%20distribute,%20and%2F%2For%20sell%20copies%20%0Aof%20the%20Open%20Design%20and%20the%20Documentation,%20together%20or%20separately,%20and%20to%20permit%20persons%20to%20whom%20the%20Open%20Design%20and%2F%2For%20%0ADocumentation%20is%20furnished%20to%20do%20so,%20subject%20to%20the%20following%20conditions%2F:%0A%0A*%20Redistributions%20of%20the%20Open%20Design%20and%2F%2For%20Documentation%20must%20retain%20the%20above%20copyright%20notice,%20this%20list%20of%20conditions%20%0Aand%20the%20following%20disclaimer.%0A%0A*%20Neither%20the%20names%20of%20XMOS,%20nor%20the%20names%20of%20its%20contributors%20may%20be%20used%20to%20endorse%20or%20promote%20products%20derived%20from%20this%20Open%20Design%20or%20the%20Documentation%20without%20specific%20prior%20written%20permission%20of%20the%20copyright%20holder.%0A%0ATHE%20OPEN%20DESIGN%20AND%20DOCUMENTATION%20ARE%20PROVIDED%20%22AS%20IS%22,%20WITHOUT%20WARRANTY%20OF%20ANY%20KIND,%20%0AEXPRESS%20OR%20IMPLIED,%20INCLUDING%20BUT%20NOT%20LIMITED%20TO%20THE%20WARRANTIES%20OF%20MERCHANTABILITY,%20FITNESS%20%0AFOR%20A%20PARTICULAR%20PURPOSE%20AND%20NONINFRINGEMENT.%20IN%20NO%20EVENT%20SHALL%20THE%20CONTRIBUTORS%20OR%20%0ACOPYRIGHT%20HOLDERS%20BE%20LIABLE%20FOR%20ANY%20CLAIM,%20DAMAGES%20OR%20OTHER%20LIABILITY,%20WHETHER%20IN%20AN%20ACTION%20OF%20%0ACONTRACT,%20TORT%20OR%20OTHERWISE,%20ARISING%20FROM,%20OUT%20OF%20OR%20IN%20CONNECTION%20WITH%20THE%20OPEN%20DESIGN%20OR%20%0ATHE%20DOCUMENTATION%20OR%20THE%20USE%20OF%20OR%20OTHER%20DEALINGS%20WITH%20THE%20OPEN%20DESIGN%20OR%20THE%20DOCUMENTATION.&background_name=Aluminium%20brushed&style=background-image%2F:%20url('%2F%2Fbg%2F%2Fmetal%2F%2Faluminum%2F_texture1642.jpg')%2F%3B&$$hashKey=07I%3B&switchMount=cherry&switchBrand=gateron&plate:true%3B&@_c=%23303030&t=%23ffffff&a:5%3B&=%0AHOME%0A%0A%0A%0A%0ANUM7&=%0AUP%0A%0A%0A%0A%0ANUM8&=%0APGUP%0A%0A%0A%0A%0ANUM9&_c=%23999999&t=%23000000%3B&=%2F%2F%0A%0A%0A%0A%0A%0A-%3B&@_c=%23303030&t=%23ffffff%3B&=%0ALEFT%0A%0A%0A%0A%0ANUM4&_a:7%3B&=NUM5&_a:5%3B&=%0ARIGHT%0A%0A%0A%0A%0ANUM6&_c=%23999999&t=%23000000%3B&=*%0A%0A%0A%0A%0A%0A+%3B&@_c=%23303030&t=%23ffffff%3B&=%0AEND%0A%0A%0A%0A%0ANUM1&_a:7%3B&=NUM2&_a:5%3B&=%0APGDN%0A%0A%0A%0A%0ANUM3&_c=%23ff0000&t=%23000000&a:7%3B&=DEL%3B&@_c=%23303030&t=%23ffffff&a:5%3B&=%0AINS%0A%0A%0A%0A%0ANUM0&_c=%23999999&t=%23000000%3B&=%0ADEL%0A%0A%0A%0A%0A,&_a:7%3B&=FN&_c=%230094ff&a:5%3B&=NUM%0A%0A%0A%0A%0A%0AENT) was made using www.keyboard-layout-editor.com.
* Middle text = Standard layer (NUMLOCK ON)
* Upper text  = Function layer
* Lower text  = Standard layer (NUMLOCK OFF)
* No text some of the layers = Transparent key (Same as standard layer)

##Todo
- [ ]  Check if anyone is interested in a group buy.
  - [ ]  What does it cost?
  - [ ]  Decide the choices of material used (3D-printed in PLA or water cut out of stainless steel)
- [ ]  Make a prototype out of water cut stainless steel.
  - [ ]  What does it weigh?
  - [ ]  Can i get any kind of finishing/treatment on the plates?
- [ ]  How can i get bluetooth compatibility and will it fit?
- [ ]  Check if the layout is compatible with different keycap profiles
- [ ]  Test the layout on a prototype
- [X] 3D-print a prototype (OLD MODEL)
  - [Pictures of the prototype (OLD MODEL)](http://imgur.com/a/AxiZH)
    - 3 parts: Bottom plate, frame and top plate.
    - Material: PLA (3D-printed)
  - [ ] 3D-print a new prototype
- [X] CAD the model (OLD MODEL)
  - [ ] CAD the new model

##Old model
The old model looks the same as the current except for the ENTER key being 2x1, covering the current ENTER and DELETE.

Could be reused if someone wants a bigger ENTER key. Though it lacks the space for a function key, reducing its number of possible keys from 31 to 16. 

##Licensing
* Hardware: XCore
* Software: GNU v3
