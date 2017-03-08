# corespring-editable-html

## Usage

Install:

  npm install --save corespring-editable-html


Import:

  import EditableHTML from 'corespring-editable-html';


Declare:

  <EditableHTML 
    placeholder="Placeholder..."
    onChange={this.htmlChanged.bind(this)} 
    model={this.state.html} />