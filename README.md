# Material Design Lite Selectors Snippets

A collection of Sublime Text selectors snippets for Material Design Lite. :eyes:

---

![mdl snippets - html](https://github.com/rasy-js/material-design-lite-snippets/blob/master/snippets.gif?raw=true)

## Menu
- [Badges](#badges)
- [Buttons](#buttons)
- [Cards](#cards)
- [Chips](#chips)
- [Dialogs](#dialogs)
- [Layout](#layout)
- [Grid](#grid)
- [Tabs](#tabs)
- [Footer](#footer)
- [Lists](#lists)
- [Progress](#progress)
- [Spinner](#spinner)
- [Menu](#menu)
- [Slider](#slider)
- [Snackbar](#snackbar)
- [Checkbox](#checkbox)
- [Radio](#radio)
- [Icon toggle](#icon-toggle)
- [Switch](#switch)
- [Table](#table)
- [Textfield](#textfield)
- [Tooltip](#tooltip)
- [Typography](#typography)
- [State Hooks](#state-hooks)
- [JS](#js)
- [Etc](#etc)
- [License](#license)

## Installation
There are 3 methods for installing this plugin.

1. Search for "Material Design Lite Selectors Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/rasy-js/material-design-lite-snippets.git`

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.

## Usage

Start typing snippet in pug or html, css, sass, scss files.

## Snippets

### Badges

| Snippet |              MDL class               |
|---------|---------------------------------------
| ma:g    | **m**dl-b**a**d**g**e                |
| ma:nb   | **m**dl-badge--**n**o-**b**ackground |
| ma:o    | **m**dl-b**a**dge--**o**verlap       |
| ma:d    | **d**ata-badge="value"               |

### Buttons

| Snippet |              MDL class               |
|---------|---------------------------------------
| mb:u    | **m**dl-**bu**tton                   |
| mb:r    | **m**dl-**b**utton--**r**aised       |
| mb:f    | **m**dl-**b**utton--**f**ab          |
| mb:mf   | **m**dl-**b**utton--**m**ini-**f**ab |
| mb:i    | **m**dl-**b**utton--**i**con         |
| mb:c    | **m**dl-**b**utton--**c**olored      |
| mb:p    | **m**dl-**b**utton--**p**rimary      |
| mb:a    | **m**dl-**b**utton--**a**ccent       |

### Cards

| Snippet |                 MDL class                 |
|---------|--------------------------------------------
| mca:r   | **m**dl-**ca**rd                          |
| mca:c   | **m**dl-**ca**rd--border                  |
| msh:d   | **m**dl-**sh**adow--N**d**p               |
| mca:t   | **m**dl-**ca**rd__**t**itle               |
| mca:tt  | **m**dl-**ca**rd__**t**itle-**t**ext      |
| mca:s   | **m**dl-**ca**rd__**s**ubtitle-text       |
| mca:m   | **m**dl-**ca**rd__**m**edia               |
| mca:st  | **m**dl-**ca**rd__**s**upporting-**t**ext |
| mca:a   | **m**dl-**ca**rd__**a**ctions             |
| mca:m   | **m**dl-**ca**rd__**m**enu                |

### Chips

| Snippet |            MDL class          |
|---------|--------------------------------
| mh:i    | **m**dl-c**hi**p              |
| mh:c    | **m**dl-c**h**ip--**c**ontact |
| mh:t    | **m**dl-c**h**ip__**t**ext    |
| mh:a    | **m**dl-c**h**ip__**a**ction  |
| mh:co   | **m**dl-c**h**ip__**co**ntact |

### Dialogs

| Snippet |                    MDL class                    |
|---------|--------------------------------------------------
| md:i    | **m**dl-**di**alog                              |
| md:t    | **m**dl-**d**ialog__**t**itle                   |
| md:c    | **m**dl-**d**ialog__**c**ontent                 |
| md:a    | **m**dl-**d**ialog__**a**ctions                 |
| md:af   | **m**dl-**d**ialog__**a**ctions--**f**ull-width |

### Layout

| Snippet |                         MDL class                          |
|---------|-------------------------------------------------------------
| ml:a    | **m**dl-**la**yout                                         |
| ml:h    | **m**dl-**l**ayout__**h**eader                             |
| ml:i    | **m**dl-**l**ayout-**i**con                                |
| ml:hr   | **m**dl-**l**ayout__header-row                             |
| ml:t    | **m**dl-**l**ayout__title                                  |
| ml:s    | **m**dl-**l**ayout-spacer                                  |
| ml:n    | **m**d**l**-**n**avigation                                 |
| ml:nl   | **m**d**l**-**n**avigation__**l**ink                       |
| ml:d    | **m**dl-**l**ayout__**d**rawer                             |
| ml:c    | **m**dl-**l**ayout__**c**ontent                            |
| ml:hs   | **m**dl-**l**ayout__**h**eader--**s**croll                 |
| ml:fd   | **m**dl-**l**ayout--**f**ixed-**d**rawer                   |
| ml:fh   | **m**dl-**l**ayout--**f**ixed-**h**eader                   |
| ml:nd   | **m**dl-**l**ayout--**n**o-**d**rawer-button               |
| ml:ndd  | **m**dl-**l**ayout--**n**o-**d**esktop-**d**rawer-button   |
| ml:l    | **m**dl-**l**ayout--**l**arget-screen-only                 |
| ml:ss   | **m**dl-**l**ayout--**s**mall-**s**creen-only              |
| ml:hw   | **m**dl-**l**ayout__**h**eader--**w**aterfall              |
| ml:hwh  | **m**dl-**l**ayout__**h**eader--**w**aterfall-**h**ide-top |
| ml:ht   | **m**dl-**l**ayout__**h**eader--**t**ransparent            |
| ml:hs   | **m**dl-**l**ayout__**h**eader--**s**eamed                 |
| ml:tb   | **m**dl-**l**ayout__**t**ab-**b**ar                        |
| ml:ta   | **m**dl-**l**ayout__**ta**b                                |
| ml:tp   | **m**dl-**l**ayout__**t**ab-**p**anel                      |
| ml:tm   | **m**dl-**l**ayout__**t**ab-**m**anual-switch              |
| ml:ft   | **m**dl-**l**ayout--**f**ixed-**t**abs                     |
| ml:ce   | **m**dl-**l**ayout-**ce**nter                              |

### Grid

| Snippet |                 MDL class                  |
|---------|---------------------------------------------
| mg:r    | **m**dl-**gr**id                           |
| mg:n    | **m**dl-**g**rid--**n**o-spacing           |
| mc:e    | **m**dl-**ce**ll                           |
| mc:c    | **m**dl-**c**ell--N-**c**ol                |
| mc:cd   | **m**dl-**c**ell--N-**c**ol-**d**esktop    |
| mc:ct   | **m**dl-**c**ell--N-**c**ol-**t**ablet     |
| mc:cp   | **m**dl-**c**ell--N-**c**ol-**p**hone      |
| mc:o    | **m**dl-**c**ell--N-**o**ffset             |
| mc:od   | **m**dl-**c**ell--N-**o**ffset-**d**esktop |
| mc:ot   | **m**dl-**c**ell--N-**o**ffset-**t**ablet  |
| mc:op   | **m**dl-**c**ell--N-**o**ffset-**p**hone   |
| mc:or   | **m**dl-**c**ell--**or**der-N              |
| mc:ord  | **m**dl-**c**ell--**or**der-N-**d**esktop  |
| mc:ort  | **m**dl-**c**ell--**or**der-N-**t**ablet   |
| mc:orp  | **m**dl-**c**ell--**or**der-N-**p**hone    |
| mc:hd   | **m**dl-**c**ell--**h**ide-**d**esktop     |
| mc:ht   | **m**dl-**c**ell--**h**ide-**t**ablet      |
| mc:hp   | **m**dl-**c**ell--**h**ide-**p**hone       |
| mc:s    | **m**dl-**c**ell--**s**tretch              |
| mc:t    | **m**dl-**c**ell--**t**op                  |
| mc:m    | **m**dl-**c**ell--**m**iddle               |
| mc:b    | **m**dl-**c**ell--**b**ottom               |

### Tabs

| Snippet |                 MDL class                  |
|---------|---------------------------------------------
| mta:b   | **m**dl-**tab**s                           |
| mta:tb  | **m**dl-**ta**bs__**t**ab-**b**ar          |
| mta:t   | **m**dl-**ta**bs__**t**ab                  |
| mta:p   | **m**dl-**ta**bs__**p**anel                |

### Footer

| Snippet |                     MDL class                      |
|---------|-----------------------------------------------------
| mm:f    | **m**dl-**m**ega-**f**ooter                        |
| mm:ft   | **m**dl-**m**ega-**f**ooter__**t**op-section       |
| mm:fl   | **m**dl-**m**ega-**f**ooter__**l**eft-section      |
| mm:fs   | **m**dl-**m**ega-**f**ooter__**s**ocial-btn        |
| mm:fr   | **m**dl-**m**ega-**f**ooter__**r**ight-section     |
| mm:fm   | **m**dl-**m**ega-**f**ooter__**m**iddle-section    |
| mm:fd   | **m**dl-**m**ega-**f**ooter__**d**rop-down-section |
| mm:fh   | **m**dl-**m**ega-**f**ooter__**h**eading           |
| mm:fll  | **m**dl-**m**ega-**f**ooter__**l**ink-**l**ist     |
| mm:fb   | **m**dl-**m**ega-**f**ooter__**b**ottom-section    |
| mmi:f   | **m**dl-**mi**ni-**f**ooter                        |
| mmi:fl  | **m**dl-**mi**ni-**f**ooter__**l**eft-section      |
| mmi:fll | **m**dl-**mi**ni-**f**ooter__**l**ink-**l**ist     |
| mmi:fr  | **m**dl-**mi**ni-**f**ooter__**r**ight-section     |
| mmi:fs  | **m**dl-**mi**ni-**f**ooter__**s**ocial-btn        |

### Lists

| Snippet  |                     MDL class                       |
|----------|------------------------------------------------------
| mli:s    | **m**dl-**lis**t                                    |
| mli:i    | **m**dl-**li**st__**i**tem                          |
| mli:it   | **m**dl-**li**st__**i**tem--**t**wo-line            |
| mli:ith  | **m**dl-**li**st__**i**tem--**th**ree-line          |
| mli:ip   | **m**dl-**li**st__**i**tem-**p**rimary-content      |
| mli:ia   | **m**dl-**li**st__**i**tem-**a**vatar               |
| mli:ii   | **m**dl-**li**st__**i**tem-**i**con                 |
| mli:is   | **m**dl-**li**st__**i**tem-**s**econdary-content    |
| mli:isi  | **m**dl-**li**st__**i**tem-**s**econdary-**i**nfo   |
| mli:isa  | **m**dl-**li**st__**i**tem-**s**econdary-**a**ction |
| mli:itb  | **m**dl-**li**st__**i**tem-**t**ext-**b**ody        |

### Progress

| Snippet  |              MDL class              |
|--------- |--------------------------------------
| mp:i     | **m**dl-progress--**i**ndeterminate |

### Spinner

| Snippet  |              MDL class              |
|----------|--------------------------------------
| ms:p     | **m**dl-**sp**inner
| ms:sc    | **m**dl-**s**pinner--**s**ingle-**c**olor

### Menu

| Snippet  |                   MDL class                    |
|----------|-------------------------------------------------
| me:n     | **m**dl-m**en**u                               |
| me:i     | **m**dl-m**e**nu__**i**tem                     |
| me:f     | **m**dl-m**e**nu__item--**f**ull-bleed-divider |
| me:t     | **m**dl-m**e**nu--**t**op-left                 |
| me:tr    | **m**dl-m**e**nu--**t**op-**r**ight            |
| me:b     | **m**dl-m**e**nu--**b**ottom-right             |

### Slider

| Snippet  |         MDL class         |
|----------|----------------------------
| mr:s     | **m**dl-**s**lide**r**    |

### Snackbar

| Snippet  |               MDL class              |
|----------|---------------------------------------
| mn:a     | **m**dl-s**na**ckbar                 |
| mn:t     | **m**dl-s**n**ackbar__**t**ext       |
| mn:ac    | **m**dl-s**n**ackbar__**ac**tion     |
| mn:at    | **m**dl-s**n**ackbar--**a**c**t**ive |

### Checkbox

| Snippet  |            MDL class            |
|----------|----------------------------------
| mk:b     | **m**dl-chec**kb**ox            |
| mk:i     | **m**dl-chec**k**box__**i**nput |
| mk:l     | **m**dl-chec**k**box__**l**abel |

### Radio

| Snippet  |             MDL class            |
|----------|-----------------------------------
| mo:r     | **m**dl-**r**adi**o**            |
| mo:rb    | **m**dl-**r**adio__butt**o**n    |
| mo:rl    | **m**dl-**r**adi**o**__**l**abel |

### Icon toggle

| Snippet  |             MDL class              |
|----------|-------------------------------------
| mic:o    | **m**dl-**ic**on-t**o**ggle        |
| mic:i    | **m**dl-**ic**on-toggle__**i**nput |
| mic:l    | **m**dl-**ic**on-toggle__**l**abel |

### Switch

| Snippet  |            MDL class          |
|----------|--------------------------------
| mw:i     | **m**dl-s**wi**tch            |
| mw:in    | **m**dl-s**w**itch__**in**put |
| mw:l     | **m**dl-s**w**itch__**l**abel |

### Table

| Snippet  |            MDL class          |
|----------|--------------------------------
| mda:t    | **m**dl-**da**ta-**t**able
| mda:s    | **m**dl-**da**ta-table--**s**electable
| mda:hs   | **m**dl-**da**ta-table__**h**eader--**s**orted-ascending
| mda:hd   | **m**dl-**da**ta-table__**h**eader--sorted-**d**escending
| mda:c    | **m**dl-**da**ta-table__**c**ell--non-numeric

### Textfield

| Snippet  |                 MDL class                 |
|----------|--------------------------------------------
| mx:t     | **m**dl-**t**e**x**tfield                 |
| mx:i     | **m**dl-te**x**tfield__**i**nput          |
| mx:l     | **m**dl-te**x**tfield__**l**abel          |
| mx:f     | **m**dl-te**x**tfield--**f**loating-label |
| mx:e     | **m**dl-te**x**tfield__**e**rror          |
| mx:ex    | **m**dl-te**x**tfield__**e**xpandable     |
| mx:h     | **m**dl-input__e**x**pandable-**h**older  |

### Tooltip

| Snippet  |            MDL class            |
|----------|----------------------------------
| moo:l    | **m**dl-t**ool**tip             |
| moo:a    | **m**dl-t**oo**ltip--l**a**rge  |
| moo:e    | **m**dl-t**oo**ltip--l**e**ft   |
| moo:r    | **m**dl-t**oo**ltip--**r**ight  |
| moo:t    | **m**dl-t**oo**ltip--**t**op    |
| moo:b    | **m**dl-t**oo**ltip--**b**ottom |

### Typography

| Snippet  |                          MDL class                              |
|----------|-----------------------------------------------------------------|
| mt:b1    | **m**dl-**t**ypography--**b**ody-**1**                          |
| mt:b1f   | **m**dl-**t**ypography--**b**ody-**1**-**f**orce-preferred-font |
| mt:b2    | **m**dl-**t**ypography--**b**ody-**2**                          |
| mt:b2c   | **m**dl-**t**ypography--**b**ody-**2**-**c**olor-contrast       |
| mt:b2f   | **m**dl-**t**ypography--**b**ody-**2**-**f**orce-preferred-font |
| mt:b     | **m**dl-**t**ypography--**b**utton                              |
| mt:c     | **m**dl-**t**ypography--**c**aption                             |
| mt:cc    | **m**dl-**t**ypography--**c**aption-**c**olor-contrast          |
| mt:d1    | **m**dl-**t**ypography--**d**isplay-**1**                       |
| mt:d1c   | **m**dl-**t**ypography--**d**isplay-**1**-**c**olor-contrast    |
| mt:d2    | **m**dl-**t**ypography--**d**isplay-**2**                       |
| mt:d3    | **m**dl-**t**ypography--**d**isplay-**3**                       |
| mt:d4    | **m**dl-**t**ypography--**d**isplay-**4**                       |
| mt:h     | **m**dl-**t**ypography--**h**eadline                            |
| mt:m     | **m**dl-**t**ypography--**m**enu                                |
| mt:s     | **m**dl-**t**ypography--**s**ubhead                             |
| mt:sc    | **m**dl-**t**ypography--**s**ubhead-**c**olor-contrast          |
| mt:ts    | **m**dl-**t**ypography--**t**able-**s**triped                   |
| mt:tc    | **m**dl-**t**ypography--**t**ext-**c**enter                     |
| mt:tj    | **m**dl-**t**ypography--**t**ext-**j**ustify                    |
| mt:tl    | **m**dl-**t**ypography--**t**ext-**l**eft                       |
| mt:tr    | **m**dl-**t**ypography--**t**ext-**r**ight                      |
| mt:tca   | **m**dl-**t**ypography--**t**ext-**ca**pitalize                 |
| mt:tlo   | **m**dl-**t**ypography--**t**ext-**lo**wercase                  |
| mt:tu    | **m**dl-**t**ypography--**t**ext-**u**ppercase                  |
| mt:tn    | **m**dl-**t**ypography--**t**ext-**n**owrap                     |
| mt:t     | **m**dl-**t**ypography--**t**itle                               |
| mt:tcc   | **m**dl-**t**ypgraphy--**t**itle-**c**olor-**c**ontrast         |

### State hooks

| Snippet  |      MDL class     | Component |
|----------|--------------------|------------
| is:a     | **is**-**a**ctive  | Layout    |
| is:i     | **is**-**i**nvalid | Textfield |

### JS

| Snippet  |             MDL class             |  Component  |
|----------|-----------------------------------|--------------
| mj:b     | **m**dl-**j**s-**b**utton         | Button      |
| mj:r     | **m**dl-**j**s-**r**ipple-effect  | Button      |
| mj:l     | **m**dl-**j**s-**l**ayout         | Layout      |
| mj:ta    | **m**dl-**j**s-**ta**bs           | Tabs        |
| mj:p     | **m**dl-**j**s-**p**rogress       | Progress    |
| mj:s     | **m**dl-**j**s-**s**pinner        | Spinner     |
| mj:m     | **m**dl-**j**s-**m**enu           | Menu        |
| mj:sl    | **m**dl-**j**s-**sl**ider         | Slider      |
| mj:c     | **m**dl-**j**s-**c**heckbox       | Checkbox    |
| mj:r     | **m**dl-**j**s-**r**adio          | Radio       |
| mj:i     | **m**dl-**j**s-**i**con-toggle    | Icon toggle |
| mj:s     | **m**dl-**j**s-**s**witch         | Switch      |
| mj:dt    | **m**dl-**j**s-**d**ata-**t**able | Data table  |
| mj:t     | **m**dl-**j**s-**t**extfield      | Textfield   |

### Etc

| Snippet  |        MDL class       |       Component       |
|----------|------------------------|------------------------
| mi:c     | **m**aterial-**ic**ons | Applicable everywhere |
| mlo:g    | **m**dl-**log**o       | Footer                |


### License

Material Design Lite Selectors Snippets - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

