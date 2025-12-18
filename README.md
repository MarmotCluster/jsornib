<h1 align="center">jsornib</h1>
<p align="center">
<img alt="logo" src="https://github.com/user-attachments/assets/cdfaf95f-a9d3-466b-a3b7-af432a4c4f17" width="256px"/>  
</p>

<p align="center">
light weighted online json formatter inspired by <b>chrome devtools</b>.
</p>

## key features

- expand/collapse by key
- merge multiple files into single `.json`.
- keyword search using a native browser feature.

## usage

switch tools by clicking logo on top. `/builder` loads in first appearance.

drop a file with extension in `.json` to structure new.

### run in your local pc

#### Option 1. open static `index.html`

1. clone the project into local using URL below.

```bash
git clone https://github.com/MarmotCluster/jsornib.git
```

2. double-click `index.html` directly and open in your primary browser.

#### Option 2. open with live-server (recommanded)

1. clone the project into local using URL below.

```bash
git clone https://github.com/MarmotCluster/jsornib.git
```

2. running `index.html` locally may require permission each time the file is opened. follow one of the steps below.

```
Open with (VS)Code > Go Live
```

requires npm and live-server installed in global.

```
npm -g install live-server
cd jsornib
live-server
```

### builder

#### import

drag and drop any file onto the wide canvas, or click `import` in the top menu to select a file.<br>

- onDrop only does wrapping imported into a single rib. open **.json** through `import rib` to edit previously created.

#### edit

`delete`: right-click on the text with `<file-size> Bytes` to isolate a value.<br>
`rename`: click on the text with filename and do rename.<br>

### viewer

import **.json** throught drag and drop or click `import` in the top menu.<br>

#### ⚠️ i cannot reach the feature.

its only able to reach by clicking icon on the top. we no longer support accessing pages directly via url path.

## have any suggestions?

create [issue](https://github.com/MarmotCluster/jsornib/issues) here.
