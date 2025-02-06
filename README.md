# RateYourMusic: Naming Guidelines for Mixes

This is a nomenclature proposal for [RateYourMusic](https://rateyourmusic.com)'s (RYM) category which encompasses DJ mixes and live electronics. 

Problems this proposal is addressing:
<ul>
	<li>Current RYM framework is unable to accommodate non-commercially released DJ mixes and live electronics, since it was created in the pre-Internet era, and is oriented around physical releases.</li>
	<li>These releases are frequently deleted and just temporarily hosted.</li>
	<li>This temporary hosting leads to incosisatent data modeling and loss of information if releases are added with literal titles.</li>
</ul>

Since majority of these recordings are going to be deleted at some point in the not so distant future, this project has **information preservation** and **consistent data modeling** as its main goals. For this to be accomplished, relevant *data fields* have to be defined:
- `ARTIST`
- `PLATFORM`
- `RADIO`
  - `RADIO_RESIDENCY`
  - `HOST` 
  - `RADIO_SHOW`
- `MIX_SERIES`
- `EVENT`
- `PROMOTION`
- `VENUE`
  - `FLOOR`
  - `CITY`
- `FESTIVAL`
  - `STAGE`
  - `YEAR`
- `COLLECTIVE`
- `LABEL`
- `TITLE`

## Title Format Structure

#### 1. Mixes on Radio, Streaming Platforms, or Part of a Series
Mixes hosted on a dedicated `PLATFORM`, aired on a `RADIO`, or are part of some `RADIO_SHOW` or `MIX_SERIES`

Format is presented below, where `|` means "OR"  
```
ARTIST - PLATFORM | RADIO | RADIO_SHOW | MIX_SERIES
```
>Artist - Future Intel  
>Artist - HÖR  
>Artist - The Lot Radio  
>Artist - NTS Radio  
>Artist - Rinse FM  
>Artist - Dekmantel Podcast 22  
>Artist - XLR8R 500

In order to differentiate between mix `TITLE` from other fields that represent some real world entity or a concept, mix titles should be enclosed with double neutral quotation marks (`"`) – Unicode code point `U+0022`. In this example from the same mix series, one mix is titled, while the other one is not. Second mix is a label showcase (De Lichting):
>Artist - isolatedmix 70: "Solar Flare"  
>Artist - isolatedmix 101: 100% De Lichting

`RADIO_SHOW` are radio shows with *distinct* name, meaning they are not eponymously named after some `ARTIST`, `COLLECTIVE`, `LABEL`, `VENUE`, or `PROMOTION`, and are usually *longer-term*:
```
ARTIST - RADIO_SHOW 
```
>Artist - Beats in Space  
>Artist - 88 Transition  
>Artist - The Space Between Spaces

#### 2. Radio Residencies
`RADIO_RESIDENCY` are recurring and usually *short-term* radio shows where `HOST` is either an `ARTIST`, `COLLECTIVE`, `LABEL`, `VENUE`, or `PROMOTION`, and are eponymously named: 
```
ARTIST - RADIO: HOST Show
```
>Artist - NTS Radio: Hessle Audio Show  
>Artist - Rinse FM: Ilian Tape Show  
>Artist - Rinse FM: MARICAS Show  
>Artist - Rinse FM: SPFDJ Show

These shows frequently have 2-hour time slots, where one hour is given to the guest. 

### Live Recordings
#### 3. Live Venue Recordings
Live recordings from a `VENUE`, where ordering of fields reflects increasing scope, i.e. from from more specific (`FLOOR`) to less specific (`CITY`): 
```
ARTIST - FLOOR, VENUE, CITY
```
>Artist - fabric, London  
>Artist - Berghain, Berlin  
>Artist - Horoom, Bassiani, Tbilisi

#### 4. Live Event and Promotion Recordings
Live recordings from named `EVENT`s or recurring `PROMOTION` events that include club nights:
```
ARTIST - (EVENT | PROMOTION) @ FLOOR, VENUE, CITY
```
>Artist - Continuum @ fabric, London  
>Artist - Drumcode Total @ Berghain, Berlin  
>Artist - subMerge @ Nowadays, NYC  
>Artist - Herrensauna @ Tresor, Berlin  
>Artist - Herrensauna @ RSO, Berlin  
>Artist - Intercell: Summer Series @ Else, Berlin  
>Artist - Vault Sessions VIII @ RADION, Amsterdam

##### 4.1 Club Nights
Live recordings from venue's flagship events.
```
ARTIST - EVENT
```
>Artist - Nowadays Nonstop  
>Artist - Tresor Klubnacht  
>Artist - RFLXN

#### 5. Live Festival Recordings
```
ARTIST - FESTIVAL YEAR: STAGE
```
>Artist - Dekmantel Festival 2017  
>Artist - Fusion Festival 2018: Turmbühne  
>Artist - Waking Life 2019: Floresta  
>Artist - Houghton Festival 2023: Outburst  
>Artist - WHOLE Festival 2024: Ambient

## Field Precedence

Fields from the first category—`PLATFORM`, `RADIO`, `RADIO_SHOW`, `MIX_SERIES`—have precedence over other fields, where colon (`:`) is used as delimiter.
`MIX_SERIES` and `VENUE` recordings, including `EVENT`: 
```
ARTIST - MIX_SERIES: (VENUE | EVENT)
```
>Artist - RA Live: OHM, Berlin  
>Artist - pi/live: Ankali, Prague  
>Artist - pi/live: poems @ OHM, Berlin
>Artist - ani/live Twenty Three: Nowadays Nonstop  
>Artist - ani/live Seventeen: Omen Wapta @ Garage Noord, Amsterdam

`MIX_SERIES` and `FESTIVAL` recordings: 
```
ARTIST - MIX_SERIES: FESTIVAL YEAR
```
>Artist - ani/live Ten: Monument Festival 2022  
>Artist - ani/live Twenty One: Transcendence 2023  
>Artist - naffcast003: Sustain-Release 2024  
>Artist - MNMT 111: Paral·lel Festival 2016

`RADIO_RESIDENCY` and `FESTIVAL` recordings. This format uses brackets (`[]`) to provide additional info, since colon (`:`) is already used:
>Artist - NTS Radio: Gigi FM Show [Stone Techno Festival 2024]

## Special Cases
### Boiler Room
```
Artist - Boiler Room CITY
```

Boiler Room recordings are not always the primary event host. Sometimes they're a part of some larger event, usually in the form of a stage at `FESTIVAL`:
```
Artist - FESTIVAL YEAR: Boiler Room
```
> Artist - Dekmantel Festival 2019: Boiler Room  
> Artist - Glitch Festival 2023: Boiler Room  
> Artist - Teletech Festival 2023: Boiler Room  
> Artist - DGTL Amsterdam 2023: Boiler Room
