# Fountain

A JavaScript parser for Fountain formated scripts that has no dependencies


## Install

    include it like any other script


## Use

    // Give it a callback
    parser.parse(string, function (output) {
      // output.title;
      // output.credit;
      // output.authors;
      // output.source;
      // output.draft_date;
      // output.date;
      // output.contact;
      // output.copyright;
      
      // output.scenes;
      
      // output.title_page_html;
      // output.script_html;
    });
    
    // Get the output directly
    var output = fountain.parse(string);
