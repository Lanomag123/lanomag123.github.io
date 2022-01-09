/* Generated on: Sat Jan 08 2022 11:00:31 GMT+0000 (Coordinated Universal Time) */
/* ==========================================================================
   normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css 
   ========================================================================== */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */html{font-family:sans-serif;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}body{margin:0}article,aside,details,figcaption,figure,footer,header,hgroup,main,menu,nav,section,summary{display:block}audio,canvas,progress,video{display:inline-block;vertical-align:baseline}audio:not([controls]){display:none;height:0}[hidden],template{display:none}a{background-color:transparent}a:active,a:hover{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}dfn{font-style:italic}h1{font-size:2em;margin:.67em 0}mark{background:#ff0;color:#000}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}img{border:0}svg:not(:root){overflow:hidden}figure{margin:1em 40px}hr{box-sizing:content-box;height:0}pre{overflow:auto}code,kbd,pre,samp{font-family:monospace,monospace;font-size:1em}button,input,optgroup,select,textarea{color:inherit;font:inherit;margin:0}button{overflow:visible}button,select{text-transform:none}button,html input[type="button"],input[type="reset"]{-webkit-appearance:button;cursor:pointer}button[disabled],html input[disabled]{cursor:default}button::-moz-focus-inner,input::-moz-focus-inner{border:0;padding:0}input{line-height:normal}input[type='checkbox'],input[type='radio']{box-sizing:border-box;padding:0}input[type='number']::-webkit-inner-spin-button,input[type='number']::-webkit-outer-spin-button{height:auto}input[type='search']{-webkit-appearance:none}input[type='search']::-webkit-search-cancel-button,input[type='search']::-webkit-search-decoration{-webkit-appearance:none}fieldset{border:1px solid #c0c0c0;margin:0 2px;padding:.35em .625em .75em}legend{border:0;padding:0}textarea{overflow:auto}optgroup{font-weight:bold}table{border-collapse:collapse;border-spacing:0}td,th{padding:0}

/* ==========================================================================
   Start of base Webflow CSS - If you're looking for some ultra-clean CSS, skip the boilerplate and see the unminified code below.
   ========================================================================== */
@font-face{font-family:'webflow-icons';src:url("data:application/x-font-ttf;charset=utf-8;base64,AAEAAAALAIAAAwAwT1MvMg8SBiUAAAC8AAAAYGNtYXDpP+a4AAABHAAAAFxnYXNwAAAAEAAAAXgAAAAIZ2x5ZmhS2XEAAAGAAAADHGhlYWQTFw3HAAAEnAAAADZoaGVhCXYFgQAABNQAAAAkaG10eCe4A1oAAAT4AAAAMGxvY2EDtALGAAAFKAAAABptYXhwABAAPgAABUQAAAAgbmFtZSoCsMsAAAVkAAABznBvc3QAAwAAAAAHNAAAACAAAwP4AZAABQAAApkCzAAAAI8CmQLMAAAB6wAzAQkAAAAAAAAAAAAAAAAAAAABEAAAAAAAAAAAAAAAAAAAAABAAADpAwPA/8AAQAPAAEAAAAABAAAAAAAAAAAAAAAgAAAAAAADAAAAAwAAABwAAQADAAAAHAADAAEAAAAcAAQAQAAAAAwACAACAAQAAQAg5gPpA//9//8AAAAAACDmAOkA//3//wAB/+MaBBcIAAMAAQAAAAAAAAAAAAAAAAABAAH//wAPAAEAAAAAAAAAAAACAAA3OQEAAAAAAQAAAAAAAAAAAAIAADc5AQAAAAABAAAAAAAAAAAAAgAANzkBAAAAAAEBIAAAAyADgAAFAAAJAQcJARcDIP5AQAGA/oBAAcABwED+gP6AQAABAOAAAALgA4AABQAAEwEXCQEH4AHAQP6AAYBAAcABwED+gP6AQAAAAwDAAOADQALAAA8AHwAvAAABISIGHQEUFjMhMjY9ATQmByEiBh0BFBYzITI2PQE0JgchIgYdARQWMyEyNj0BNCYDIP3ADRMTDQJADRMTDf3ADRMTDQJADRMTDf3ADRMTDQJADRMTAsATDSANExMNIA0TwBMNIA0TEw0gDRPAEw0gDRMTDSANEwAAAAABAJ0AtAOBApUABQAACQIHCQEDJP7r/upcAXEBcgKU/usBFVz+fAGEAAAAAAL//f+9BAMDwwAEAAkAABcBJwEXAwE3AQdpA5ps/GZsbAOabPxmbEMDmmz8ZmwDmvxmbAOabAAAAgAA/8AEAAPAAB0AOwAABSInLgEnJjU0Nz4BNzYzMTIXHgEXFhUUBw4BBwYjNTI3PgE3NjU0Jy4BJyYjMSIHDgEHBhUUFx4BFxYzAgBqXV6LKCgoKIteXWpqXV6LKCgoKIteXWpVSktvICEhIG9LSlVVSktvICEhIG9LSlVAKCiLXl1qal1eiygoKCiLXl1qal1eiygoZiEgb0tKVVVKS28gISEgb0tKVVVKS28gIQABAAABwAIAA8AAEgAAEzQ3PgE3NjMxFSIHDgEHBhUxIwAoKIteXWpVSktvICFmAcBqXV6LKChmISBvS0pVAAAAAgAA/8AFtgPAADIAOgAAARYXHgEXFhUUBw4BBwYHIxUhIicuAScmNTQ3PgE3NjMxOAExNDc+ATc2MzIXHgEXFhcVATMJATMVMzUEjD83NlAXFxYXTjU1PQL8kz01Nk8XFxcXTzY1PSIjd1BQWlJJSXInJw3+mdv+2/7c25MCUQYcHFg5OUA/ODlXHBwIAhcXTzY1PTw1Nk8XF1tQUHcjIhwcYUNDTgL+3QFt/pOTkwABAAAAAQAAmM7nP18PPPUACwQAAAAAANciZKUAAAAA1yJkpf/9/70FtgPDAAAACAACAAAAAAAAAAEAAAPA/8AAAAW3//3//QW2AAEAAAAAAAAAAAAAAAAAAAAMBAAAAAAAAAAAAAAAAgAAAAQAASAEAADgBAAAwAQAAJ0EAP/9BAAAAAQAAAAFtwAAAAAAAAAKABQAHgAyAEYAjACiAL4BFgE2AY4AAAABAAAADAA8AAMAAAAAAAIAAAAAAAAAAAAAAAAAAAAAAAAADgCuAAEAAAAAAAEADQAAAAEAAAAAAAIABwCWAAEAAAAAAAMADQBIAAEAAAAAAAQADQCrAAEAAAAAAAUACwAnAAEAAAAAAAYADQBvAAEAAAAAAAoAGgDSAAMAAQQJAAEAGgANAAMAAQQJAAIADgCdAAMAAQQJAAMAGgBVAAMAAQQJAAQAGgC4AAMAAQQJAAUAFgAyAAMAAQQJAAYAGgB8AAMAAQQJAAoANADsd2ViZmxvdy1pY29ucwB3AGUAYgBmAGwAbwB3AC0AaQBjAG8AbgBzVmVyc2lvbiAxLjAAVgBlAHIAcwBpAG8AbgAgADEALgAwd2ViZmxvdy1pY29ucwB3AGUAYgBmAGwAbwB3AC0AaQBjAG8AbgBzd2ViZmxvdy1pY29ucwB3AGUAYgBmAGwAbwB3AC0AaQBjAG8AbgBzUmVndWxhcgBSAGUAZwB1AGwAYQByd2ViZmxvdy1pY29ucwB3AGUAYgBmAGwAbwB3AC0AaQBjAG8AbgBzRm9udCBnZW5lcmF0ZWQgYnkgSWNvTW9vbi4ARgBvAG4AdAAgAGcAZQBuAGUAcgBhAHQAZQBkACAAYgB5ACAASQBjAG8ATQBvAG8AbgAuAAAAAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA==") format('truetype');font-weight:normal;font-style:normal}[class^="w-icon-"],[class*=" w-icon-"]{font-family:'webflow-icons' !important;speak:none;font-style:normal;font-weight:normal;font-variant:normal;text-transform:none;line-height:1;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.w-icon-slider-right:before{content:"\e600"}.w-icon-slider-left:before{content:"\e601"}.w-icon-nav-menu:before{content:"\e602"}.w-icon-arrow-down:before,.w-icon-dropdown-toggle:before{content:"\e603"}.w-icon-file-upload-remove:before{content:"\e900"}.w-icon-file-upload-icon:before{content:"\e903"}*{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}html{height:100%}body{margin:0;min-height:100%;background-color:#fff;font-family:Arial,sans-serif;font-size:14px;line-height:20px;color:#333}img{max-width:100%;vertical-align:middle;display:inline-block}html.w-mod-touch *{background-attachment:scroll !important}.w-block{display:block}.w-inline-block{max-width:100%;display:inline-block}.w-clearfix:before,.w-clearfix:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-clearfix:after{clear:both}.w-hidden{display:none}.w-button{display:inline-block;padding:9px 15px;background-color:#3898EC;color:white;border:0;line-height:inherit;text-decoration:none;cursor:pointer;border-radius:0}input.w-button{-webkit-appearance:button}html[data-w-dynpage] [data-w-cloak]{color:transparent !important}.w-webflow-badge,.w-webflow-badge *{position:static;left:auto;top:auto;right:auto;bottom:auto;z-index:auto;display:block;visibility:visible;overflow:visible;overflow-x:visible;overflow-y:visible;box-sizing:border-box;width:auto;height:auto;max-height:none;max-width:none;min-height:0;min-width:0;margin:0;padding:0;float:none;clear:none;border:0 none transparent;border-radius:0;background:none;background-image:none;background-position:0 0;background-size:auto auto;background-repeat:repeat;background-origin:padding-box;background-clip:border-box;background-attachment:scroll;background-color:transparent;box-shadow:none;opacity:1;transform:none;transition:none;direction:ltr;font-family:inherit;font-weight:inherit;color:inherit;font-size:inherit;line-height:inherit;font-style:inherit;font-variant:inherit;text-align:inherit;letter-spacing:inherit;text-decoration:inherit;text-indent:0;text-transform:inherit;list-style-type:disc;text-shadow:none;font-smoothing:auto;vertical-align:baseline;cursor:inherit;white-space:inherit;word-break:normal;word-spacing:normal;word-wrap:normal}.w-webflow-badge{position:fixed !important;display:inline-block !important;visibility:visible !important;z-index:2147483647 !important;top:auto !important;right:12px !important;bottom:12px !important;left:auto !important;color:#AAADB0 !important;background-color:#fff !important;border-radius:3px !important;padding:6px 8px 6px 6px !important;font-size:12px !important;opacity:1 !important;line-height:14px !important;text-decoration:none !important;transform:none !important;margin:0 !important;width:auto !important;height:auto !important;overflow:visible !important;white-space:nowrap;box-shadow:0 0 0 1px rgba(0,0,0,0.1),0 1px 3px rgba(0,0,0,0.1);cursor:pointer}.w-webflow-badge>img{display:inline-block !important;visibility:visible !important;opacity:1 !important;vertical-align:middle !important}h1,h2,h3,h4,h5,h6{font-weight:bold;margin-bottom:10px}h1{font-size:38px;line-height:44px;margin-top:20px}h2{font-size:32px;line-height:36px;margin-top:20px}h3{font-size:24px;line-height:30px;margin-top:20px}h4{font-size:18px;line-height:24px;margin-top:10px}h5{font-size:14px;line-height:20px;margin-top:10px}h6{font-size:12px;line-height:18px;margin-top:10px}p{margin-top:0;margin-bottom:10px}blockquote{margin:0 0 10px 0;padding:10px 20px;border-left:5px solid #E2E2E2;font-size:18px;line-height:22px}figure{margin:0;margin-bottom:10px}figcaption{margin-top:5px;text-align:center}ul,ol{margin-top:0;margin-bottom:10px;padding-left:40px}.w-list-unstyled{padding-left:0;list-style:none}.w-embed:before,.w-embed:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-embed:after{clear:both}.w-video{width:100%;position:relative;padding:0}.w-video iframe,.w-video object,.w-video embed{position:absolute;top:0;left:0;width:100%;height:100%}fieldset{padding:0;margin:0;border:0}button,html input[type='button'],input[type='reset']{border:0;cursor:pointer;-webkit-appearance:button}.w-form{margin:0 0 15px}.w-form-done{display:none;padding:20px;text-align:center;background-color:#dddddd}.w-form-fail{display:none;margin-top:10px;padding:10px;background-color:#ffdede}label{display:block;margin-bottom:5px;font-weight:bold}.w-input,.w-select{display:block;width:100%;height:38px;padding:8px 12px;margin-bottom:10px;font-size:14px;line-height:1.42857143;color:#333333;vertical-align:middle;background-color:#ffffff;border:1px solid #cccccc}.w-input:-moz-placeholder,.w-select:-moz-placeholder{color:#999}.w-input::-moz-placeholder,.w-select::-moz-placeholder{color:#999;opacity:1}.w-input:-ms-input-placeholder,.w-select:-ms-input-placeholder{color:#999}.w-input::-webkit-input-placeholder,.w-select::-webkit-input-placeholder{color:#999}.w-input:focus,.w-select:focus{border-color:#3898EC;outline:0}.w-input[disabled],.w-select[disabled],.w-input[readonly],.w-select[readonly],fieldset[disabled] .w-input,fieldset[disabled] .w-select{cursor:not-allowed;background-color:#eeeeee}textarea.w-input,textarea.w-select{height:auto}.w-select{background-color:#f3f3f3}.w-select[multiple]{height:auto}.w-form-label{display:inline-block;cursor:pointer;font-weight:normal;margin-bottom:0}.w-radio{display:block;margin-bottom:5px;padding-left:20px}.w-radio:before,.w-radio:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-radio:after{clear:both}.w-radio-input{margin:4px 0 0;margin-top:1px \9;line-height:normal;float:left;margin-left:-20px}.w-radio-input{margin-top:3px}.w-file-upload{display:block;margin-bottom:10px}.w-file-upload-input{width:.1px;height:.1px;opacity:0;overflow:hidden;position:absolute;z-index:-100}.w-file-upload-default,.w-file-upload-uploading,.w-file-upload-success{display:inline-block;color:#333333}.w-file-upload-error{display:block;margin-top:10px}.w-file-upload-default.w-hidden,.w-file-upload-uploading.w-hidden,.w-file-upload-error.w-hidden,.w-file-upload-success.w-hidden{display:none}.w-file-upload-uploading-btn{display:flex;font-size:14px;font-weight:normal;cursor:pointer;margin:0;padding:8px 12px;border:1px solid #cccccc;background-color:#fafafa}.w-file-upload-file{display:flex;flex-grow:1;justify-content:space-between;margin:0;padding:8px 9px 8px 11px;border:1px solid #cccccc;background-color:#fafafa}.w-file-upload-file-name{font-size:14px;font-weight:normal;display:block}.w-file-remove-link{margin-top:3px;margin-left:10px;width:auto;height:auto;padding:3px;display:block;cursor:pointer}.w-icon-file-upload-remove{margin:auto;font-size:10px}.w-file-upload-error-msg{display:inline-block;color:#ea384c;padding:2px 0}.w-file-upload-info{display:inline-block;line-height:38px;padding:0 12px}.w-file-upload-label{display:inline-block;font-size:14px;font-weight:normal;cursor:pointer;margin:0;padding:8px 12px;border:1px solid #cccccc;background-color:#fafafa}.w-icon-file-upload-icon,.w-icon-file-upload-uploading{display:inline-block;margin-right:8px;width:20px}.w-icon-file-upload-uploading{height:20px}.w-container{margin-left:auto;margin-right:auto;max-width:940px}.w-container:before,.w-container:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-container:after{clear:both}.w-container .w-row{margin-left:-10px;margin-right:-10px}.w-row:before,.w-row:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-row:after{clear:both}.w-row .w-row{margin-left:0;margin-right:0}.w-col{position:relative;float:left;width:100%;min-height:1px;padding-left:10px;padding-right:10px}.w-col .w-col{padding-left:0;padding-right:0}.w-col-1{width:8.33333333%}.w-col-2{width:16.66666667%}.w-col-3{width:25%}.w-col-4{width:33.33333333%}.w-col-5{width:41.66666667%}.w-col-6{width:50%}.w-col-7{width:58.33333333%}.w-col-8{width:66.66666667%}.w-col-9{width:75%}.w-col-10{width:83.33333333%}.w-col-11{width:91.66666667%}.w-col-12{width:100%}.w-hidden-main{display:none !important}@media screen and (max-width:991px){.w-container{max-width:728px}.w-hidden-main{display:inherit !important}.w-hidden-medium{display:none !important}.w-col-medium-1{width:8.33333333%}.w-col-medium-2{width:16.66666667%}.w-col-medium-3{width:25%}.w-col-medium-4{width:33.33333333%}.w-col-medium-5{width:41.66666667%}.w-col-medium-6{width:50%}.w-col-medium-7{width:58.33333333%}.w-col-medium-8{width:66.66666667%}.w-col-medium-9{width:75%}.w-col-medium-10{width:83.33333333%}.w-col-medium-11{width:91.66666667%}.w-col-medium-12{width:100%}.w-col-stack{width:100%;left:auto;right:auto}}@media screen and (max-width:767px){.w-hidden-main{display:inherit !important}.w-hidden-medium{display:inherit !important}.w-hidden-small{display:none !important}.w-row,.w-container .w-row{margin-left:0;margin-right:0}.w-col{width:100%;left:auto;right:auto}.w-col-small-1{width:8.33333333%}.w-col-small-2{width:16.66666667%}.w-col-small-3{width:25%}.w-col-small-4{width:33.33333333%}.w-col-small-5{width:41.66666667%}.w-col-small-6{width:50%}.w-col-small-7{width:58.33333333%}.w-col-small-8{width:66.66666667%}.w-col-small-9{width:75%}.w-col-small-10{width:83.33333333%}.w-col-small-11{width:91.66666667%}.w-col-small-12{width:100%}}@media screen and (max-width:479px){.w-container{max-width:none}.w-hidden-main{display:inherit !important}.w-hidden-medium{display:inherit !important}.w-hidden-small{display:inherit !important}.w-hidden-tiny{display:none !important}.w-col{width:100%}.w-col-tiny-1{width:8.33333333%}.w-col-tiny-2{width:16.66666667%}.w-col-tiny-3{width:25%}.w-col-tiny-4{width:33.33333333%}.w-col-tiny-5{width:41.66666667%}.w-col-tiny-6{width:50%}.w-col-tiny-7{width:58.33333333%}.w-col-tiny-8{width:66.66666667%}.w-col-tiny-9{width:75%}.w-col-tiny-10{width:83.33333333%}.w-col-tiny-11{width:91.66666667%}.w-col-tiny-12{width:100%}}.w-widget{position:relative}.w-widget-map{width:100%;height:400px}.w-widget-map label{width:auto;display:inline}.w-widget-map img{max-width:inherit}.w-widget-map .gm-style-iw{text-align:center}.w-widget-map .gm-style-iw>button{display:none !important}.w-widget-twitter{overflow:hidden}.w-widget-twitter-count-shim{display:inline-block;vertical-align:top;position:relative;width:28px;height:20px;text-align:center;background:white;border:#758696 solid 1px;border-radius:3px}.w-widget-twitter-count-shim *{pointer-events:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.w-widget-twitter-count-shim .w-widget-twitter-count-inner{position:relative;font-size:15px;line-height:12px;text-align:center;color:#999;font-family:serif}.w-widget-twitter-count-shim .w-widget-twitter-count-clear{position:relative;display:block}.w-widget-twitter-count-shim.w--large{width:36px;height:28px}.w-widget-twitter-count-shim.w--large .w-widget-twitter-count-inner{font-size:18px;line-height:18px}.w-widget-twitter-count-shim:not(.w--vertical){margin-left:5px;margin-right:8px}.w-widget-twitter-count-shim:not(.w--vertical).w--large{margin-left:6px}.w-widget-twitter-count-shim:not(.w--vertical):before,.w-widget-twitter-count-shim:not(.w--vertical):after{top:50%;left:0;border:solid transparent;content:" ";height:0;width:0;position:absolute;pointer-events:none}.w-widget-twitter-count-shim:not(.w--vertical):before{border-color:rgba(117,134,150,0);border-right-color:#5d6c7b;border-width:4px;margin-left:-9px;margin-top:-4px}.w-widget-twitter-count-shim:not(.w--vertical).w--large:before{border-width:5px;margin-left:-10px;margin-top:-5px}.w-widget-twitter-count-shim:not(.w--vertical):after{border-color:rgba(255,255,255,0);border-right-color:white;border-width:4px;margin-left:-8px;margin-top:-4px}.w-widget-twitter-count-shim:not(.w--vertical).w--large:after{border-width:5px;margin-left:-9px;margin-top:-5px}.w-widget-twitter-count-shim.w--vertical{width:61px;height:33px;margin-bottom:8px}.w-widget-twitter-count-shim.w--vertical:before,.w-widget-twitter-count-shim.w--vertical:after{top:100%;left:50%;border:solid transparent;content:" ";height:0;width:0;position:absolute;pointer-events:none}.w-widget-twitter-count-shim.w--vertical:before{border-color:rgba(117,134,150,0);border-top-color:#5d6c7b;border-width:5px;margin-left:-5px}.w-widget-twitter-count-shim.w--vertical:after{border-color:rgba(255,255,255,0);border-top-color:white;border-width:4px;margin-left:-4px}.w-widget-twitter-count-shim.w--vertical .w-widget-twitter-count-inner{font-size:18px;line-height:22px}.w-widget-twitter-count-shim.w--vertical.w--large{width:76px}.w-widget-gplus{overflow:hidden}.w-background-video{position:relative;overflow:hidden;height:500px;color:white}.w-background-video>video{background-size:cover;background-position:50% 50%;position:absolute;margin:auto;width:100%;height:100%;right:-100%;bottom:-100%;top:-100%;left:-100%;object-fit:cover;z-index:-100}.w-background-video>video::-webkit-media-controls-start-playback-button{display:none !important;-webkit-appearance:none}.w-slider{position:relative;height:300px;text-align:center;background:#dddddd;clear:both;-webkit-tap-highlight-color:rgba(0,0,0,0);tap-highlight-color:rgba(0,0,0,0)}.w-slider-mask{position:relative;display:block;overflow:hidden;z-index:1;left:0;right:0;height:100%;white-space:nowrap}.w-slide{position:relative;display:inline-block;vertical-align:top;width:100%;height:100%;white-space:normal;text-align:left}.w-slider-nav{position:absolute;z-index:2;top:auto;right:0;bottom:0;left:0;margin:auto;padding-top:10px;height:40px;text-align:center;-webkit-tap-highlight-color:rgba(0,0,0,0);tap-highlight-color:rgba(0,0,0,0)}.w-slider-nav.w-round>div{border-radius:100%}.w-slider-nav.w-num>div{width:auto;height:auto;padding:.2em .5em;font-size:inherit;line-height:inherit}.w-slider-nav.w-shadow>div{box-shadow:0 0 3px rgba(51,51,51,0.4)}.w-slider-nav-invert{color:#fff}.w-slider-nav-invert>div{background-color:rgba(34,34,34,0.4)}.w-slider-nav-invert>div.w-active{background-color:#222}.w-slider-dot{position:relative;display:inline-block;width:1em;height:1em;background-color:rgba(255,255,255,0.4);cursor:pointer;margin:0 3px .5em;transition:background-color 100ms,color 100ms}.w-slider-dot.w-active{background-color:#fff}.w-slider-dot:focus{outline:none;box-shadow:0 0 0 2px #fff}.w-slider-dot:focus.w-active{box-shadow:none}.w-slider-arrow-left,.w-slider-arrow-right{position:absolute;width:80px;top:0;right:0;bottom:0;left:0;margin:auto;cursor:pointer;overflow:hidden;color:white;font-size:40px;-webkit-tap-highlight-color:rgba(0,0,0,0);tap-highlight-color:rgba(0,0,0,0);-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.w-slider-arrow-left [class^='w-icon-'],.w-slider-arrow-right [class^='w-icon-'],.w-slider-arrow-left [class*=' w-icon-'],.w-slider-arrow-right [class*=' w-icon-']{position:absolute}.w-slider-arrow-left:focus,.w-slider-arrow-right:focus{outline:0}.w-slider-arrow-left{z-index:3;right:auto}.w-slider-arrow-right{z-index:4;left:auto}.w-icon-slider-left,.w-icon-slider-right{top:0;right:0;bottom:0;left:0;margin:auto;width:1em;height:1em}.w-slider-aria-label{border:0;clip:rect(0 0 0 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;width:1px}.w-slider-force-show{display:block !important}.w-dropdown{display:inline-block;position:relative;text-align:left;margin-left:auto;margin-right:auto;z-index:900}.w-dropdown-btn,.w-dropdown-toggle,.w-dropdown-link{position:relative;vertical-align:top;text-decoration:none;color:#222222;padding:20px;text-align:left;margin-left:auto;margin-right:auto;white-space:nowrap}.w-dropdown-toggle{-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;display:inline-block;cursor:pointer;padding-right:40px}.w-dropdown-toggle:focus{outline:0}.w-icon-dropdown-toggle{position:absolute;top:0;right:0;bottom:0;margin:auto;margin-right:20px;width:1em;height:1em}.w-dropdown-list{position:absolute;background:#dddddd;display:none;min-width:100%}.w-dropdown-list.w--open{display:block}.w-dropdown-link{padding:10px 20px;display:block;color:#222222}.w-dropdown-link.w--current{color:#0082f3}.w-dropdown-link:focus{outline:0}@media screen and (max-width:767px){.w-nav-brand{padding-left:10px}}.w-lightbox-backdrop{color:#000;cursor:auto;font-family:serif;font-size:medium;font-style:normal;font-variant:normal;font-weight:normal;letter-spacing:normal;line-height:normal;list-style:disc;text-align:start;text-indent:0;text-shadow:none;text-transform:none;visibility:visible;white-space:normal;word-break:normal;word-spacing:normal;word-wrap:normal;position:fixed;top:0;right:0;bottom:0;left:0;color:#fff;font-family:"Helvetica Neue",Helvetica,Ubuntu,"Segoe UI",Verdana,sans-serif;font-size:17px;line-height:1.2;font-weight:300;text-align:center;background:rgba(0,0,0,0.9);z-index:2000;outline:0;opacity:0;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;-webkit-tap-highlight-color:transparent;-webkit-transform:translate(0, 0)}.w-lightbox-backdrop,.w-lightbox-container{height:100%;overflow:auto;-webkit-overflow-scrolling:touch}.w-lightbox-content{position:relative;height:100vh;overflow:hidden}.w-lightbox-view{position:absolute;width:100vw;height:100vh;opacity:0}.w-lightbox-view:before{content:"";height:100vh}.w-lightbox-group,.w-lightbox-group .w-lightbox-view,.w-lightbox-group .w-lightbox-view:before{height:86vh}.w-lightbox-frame,.w-lightbox-view:before{display:inline-block;vertical-align:middle}.w-lightbox-figure{position:relative;margin:0}.w-lightbox-group .w-lightbox-figure{cursor:pointer}.w-lightbox-img{width:auto;height:auto;max-width:none}.w-lightbox-image{display:block;float:none;max-width:100vw;max-height:100vh}.w-lightbox-group .w-lightbox-image{max-height:86vh}.w-lightbox-caption{position:absolute;right:0;bottom:0;left:0;padding:.5em 1em;background:rgba(0,0,0,0.4);text-align:left;text-overflow:ellipsis;white-space:nowrap;overflow:hidden}.w-lightbox-embed{position:absolute;top:0;right:0;bottom:0;left:0;width:100%;height:100%}.w-lightbox-control{position:absolute;top:0;width:4em;background-size:24px;background-repeat:no-repeat;background-position:center;cursor:pointer;-webkit-transition:all .3s;transition:all .3s}.w-lightbox-left{display:none;bottom:0;left:0;background-image:url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii0yMCAwIDI0IDQwIiB3aWR0aD0iMjQiIGhlaWdodD0iNDAiPjxnIHRyYW5zZm9ybT0icm90YXRlKDQ1KSI+PHBhdGggZD0ibTAgMGg1djIzaDIzdjVoLTI4eiIgb3BhY2l0eT0iLjQiLz48cGF0aCBkPSJtMSAxaDN2MjNoMjN2M2gtMjZ6IiBmaWxsPSIjZmZmIi8+PC9nPjwvc3ZnPg==")}.w-lightbox-right{display:none;right:0;bottom:0;background-image:url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii00IDAgMjQgNDAiIHdpZHRoPSIyNCIgaGVpZ2h0PSI0MCI+PGcgdHJhbnNmb3JtPSJyb3RhdGUoNDUpIj48cGF0aCBkPSJtMC0waDI4djI4aC01di0yM2gtMjN6IiBvcGFjaXR5PSIuNCIvPjxwYXRoIGQ9Im0xIDFoMjZ2MjZoLTN2LTIzaC0yM3oiIGZpbGw9IiNmZmYiLz48L2c+PC9zdmc+")}.w-lightbox-close{right:0;height:2.6em;background-image:url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii00IDAgMTggMTciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxNyI+PGcgdHJhbnNmb3JtPSJyb3RhdGUoNDUpIj48cGF0aCBkPSJtMCAwaDd2LTdoNXY3aDd2NWgtN3Y3aC01di03aC03eiIgb3BhY2l0eT0iLjQiLz48cGF0aCBkPSJtMSAxaDd2LTdoM3Y3aDd2M2gtN3Y3aC0zdi03aC03eiIgZmlsbD0iI2ZmZiIvPjwvZz48L3N2Zz4=");background-size:18px}.w-lightbox-strip{position:absolute;bottom:0;left:0;right:0;padding:0 1vh;line-height:0;white-space:nowrap;overflow-x:auto;overflow-y:hidden}.w-lightbox-item{display:inline-block;width:10vh;padding:2vh 1vh;box-sizing:content-box;cursor:pointer;-webkit-transform:translate3d(0, 0, 0)}.w-lightbox-active{opacity:.3}.w-lightbox-thumbnail{position:relative;height:10vh;background:#222;overflow:hidden}.w-lightbox-thumbnail-image{position:absolute;top:0;left:0}.w-lightbox-thumbnail .w-lightbox-tall{top:50%;width:100%;-webkit-transform:translate(0, -50%);-ms-transform:translate(0, -50%);transform:translate(0, -50%)}.w-lightbox-thumbnail .w-lightbox-wide{left:50%;height:100%;-webkit-transform:translate(-50%, 0);-ms-transform:translate(-50%, 0);transform:translate(-50%, 0)}.w-lightbox-spinner{position:absolute;top:50%;left:50%;box-sizing:border-box;width:40px;height:40px;margin-top:-20px;margin-left:-20px;border:5px solid rgba(0,0,0,0.4);border-radius:50%;-webkit-animation:spin .8s infinite linear;animation:spin .8s infinite linear}.w-lightbox-spinner:after{content:"";position:absolute;top:-4px;right:-4px;bottom:-4px;left:-4px;border:3px solid transparent;border-bottom-color:#fff;border-radius:50%}.w-lightbox-hide{display:none}.w-lightbox-noscroll{overflow:hidden}@media (min-width:768px){.w-lightbox-content{height:96vh;margin-top:2vh}.w-lightbox-view,.w-lightbox-view:before{height:96vh}.w-lightbox-group,.w-lightbox-group .w-lightbox-view,.w-lightbox-group .w-lightbox-view:before{height:84vh}.w-lightbox-image{max-width:96vw;max-height:96vh}.w-lightbox-group .w-lightbox-image{max-width:82.3vw;max-height:84vh}.w-lightbox-left,.w-lightbox-right{display:block;opacity:.5}.w-lightbox-close{opacity:.8}.w-lightbox-control:hover{opacity:1}}.w-lightbox-inactive,.w-lightbox-inactive:hover{opacity:0}.w-richtext:before,.w-richtext:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-richtext:after{clear:both}.w-richtext[contenteditable="true"]:before,.w-richtext[contenteditable="true"]:after{white-space:initial}.w-richtext ol,.w-richtext ul{overflow:hidden}.w-richtext .w-richtext-figure-selected.w-richtext-figure-type-video div:after,.w-richtext .w-richtext-figure-selected[data-rt-type="video"] div:after{outline:2px solid #2895f7}.w-richtext .w-richtext-figure-selected.w-richtext-figure-type-image div,.w-richtext .w-richtext-figure-selected[data-rt-type="image"] div{outline:2px solid #2895f7}.w-richtext figure.w-richtext-figure-type-video>div:after,.w-richtext figure[data-rt-type="video"]>div:after{content:'';position:absolute;display:none;left:0;top:0;right:0;bottom:0}.w-richtext figure{position:relative;max-width:60%}.w-richtext figure>div:before{cursor:default !important}.w-richtext figure img{width:100%}.w-richtext figure figcaption.w-richtext-figcaption-placeholder{opacity:.6}.w-richtext figure div{font-size:0;color:transparent}.w-richtext figure.w-richtext-figure-type-image,.w-richtext figure[data-rt-type="image"]{display:table}.w-richtext figure.w-richtext-figure-type-image>div,.w-richtext figure[data-rt-type="image"]>div{display:inline-block}.w-richtext figure.w-richtext-figure-type-image>figcaption,.w-richtext figure[data-rt-type="image"]>figcaption{display:table-caption;caption-side:bottom}.w-richtext figure.w-richtext-figure-type-video,.w-richtext figure[data-rt-type="video"]{width:60%;height:0}.w-richtext figure.w-richtext-figure-type-video iframe,.w-richtext figure[data-rt-type="video"] iframe{position:absolute;top:0;left:0;width:100%;height:100%}.w-richtext figure.w-richtext-figure-type-video>div,.w-richtext figure[data-rt-type="video"]>div{width:100%}.w-richtext figure.w-richtext-align-center{margin-right:auto;margin-left:auto;clear:both}.w-richtext figure.w-richtext-align-center.w-richtext-figure-type-image>div,.w-richtext figure.w-richtext-align-center[data-rt-type="image"]>div{max-width:100%}.w-richtext figure.w-richtext-align-normal{clear:both}.w-richtext figure.w-richtext-align-fullwidth{width:100%;max-width:100%;text-align:center;clear:both;display:block;margin-right:auto;margin-left:auto}.w-richtext figure.w-richtext-align-fullwidth>div{display:inline-block;padding-bottom:inherit}.w-richtext figure.w-richtext-align-fullwidth>figcaption{display:block}.w-richtext figure.w-richtext-align-floatleft{float:left;margin-right:15px;clear:none}.w-richtext figure.w-richtext-align-floatright{float:right;margin-left:15px;clear:none}.w-nav{position:relative;background:#dddddd;z-index:1000}.w-nav:before,.w-nav:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-nav:after{clear:both}.w-nav-brand{position:relative;float:left;text-decoration:none;color:#333333}.w-nav-link{position:relative;display:inline-block;vertical-align:top;text-decoration:none;color:#222222;padding:20px;text-align:left;margin-left:auto;margin-right:auto}.w-nav-link.w--current{color:#0082f3}.w-nav-menu{position:relative;float:right}[data-nav-menu-open]{display:block !important;position:absolute;top:100%;left:0;right:0;background:#C8C8C8;text-align:center;overflow:visible;min-width:200px}.w--nav-link-open{display:block;position:relative}.w-nav-overlay{position:absolute;overflow:hidden;display:none;top:100%;left:0;right:0;width:100%}.w-nav-overlay [data-nav-menu-open]{top:0}.w-nav[data-animation="over-left"] .w-nav-overlay{width:auto}.w-nav[data-animation="over-left"] .w-nav-overlay,.w-nav[data-animation="over-left"] [data-nav-menu-open]{right:auto;z-index:1;top:0}.w-nav[data-animation="over-right"] .w-nav-overlay{width:auto}.w-nav[data-animation="over-right"] .w-nav-overlay,.w-nav[data-animation="over-right"] [data-nav-menu-open]{left:auto;z-index:1;top:0}.w-nav-button{position:relative;float:right;padding:18px;font-size:24px;display:none;cursor:pointer;-webkit-tap-highlight-color:rgba(0,0,0,0);tap-highlight-color:rgba(0,0,0,0);-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none}.w-nav-button:focus{outline:0}.w-nav-button.w--open{background-color:#C8C8C8;color:white}.w-nav[data-collapse="all"] .w-nav-menu{display:none}.w-nav[data-collapse="all"] .w-nav-button{display:block}.w--nav-dropdown-open{display:block}.w--nav-dropdown-toggle-open{display:block}.w--nav-dropdown-list-open{position:static}@media screen and (max-width:991px){.w-nav[data-collapse="medium"] .w-nav-menu{display:none}.w-nav[data-collapse="medium"] .w-nav-button{display:block}}@media screen and (max-width:767px){.w-nav[data-collapse="small"] .w-nav-menu{display:none}.w-nav[data-collapse="small"] .w-nav-button{display:block}.w-nav-brand{padding-left:10px}}@media screen and (max-width:479px){.w-nav[data-collapse="tiny"] .w-nav-menu{display:none}.w-nav[data-collapse="tiny"] .w-nav-button{display:block}}.w-tabs{position:relative}.w-tabs:before,.w-tabs:after{content:" ";display:table;grid-column-start:1;grid-row-start:1;grid-column-end:2;grid-row-end:2}.w-tabs:after{clear:both}.w-tab-menu{position:relative}.w-tab-link{position:relative;display:inline-block;vertical-align:top;text-decoration:none;padding:9px 30px;text-align:left;cursor:pointer;color:#222222;background-color:#dddddd}.w-tab-link.w--current{background-color:#C8C8C8}.w-tab-link:focus{outline:0}.w-tab-content{position:relative;display:block;overflow:hidden}.w-tab-pane{position:relative;display:none}.w--tab-active{display:block}@media screen and (max-width:479px){.w-tab-link{display:block}}.w-ix-emptyfix:after{content:""}@keyframes spin{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}.w-dyn-empty{padding:10px;background-color:#dddddd}.w-dyn-hide{display:none !important}.w-dyn-bind-empty{display:none !important}.w-condition-invisible{display:none !important}

/* ==========================================================================
   Start of custom Webflow CSS
   ========================================================================== */
.w-layout-grid {
  display: -ms-grid;
  display: grid;
  grid-auto-columns: 1fr;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
  grid-row-gap: 16px;
  grid-column-gap: 16px;
}

.nav-link {
  top: 10px;
  display: none;
  margin-right: 15px;
  padding: 6px 12px;
  border: 1px none #000;
  border-radius: 20px;
  background-color: #000;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-weight: 400;
  letter-spacing: 2px;
  text-decoration: none;
  text-transform: uppercase;
  white-space: normal;
  background-clip: padding-box;
  -webkit-text-fill-color: inherit;
}

.nav-link-middle {
  top: 10px;
  margin-right: 0px;
  padding: 5px 20px;
  border-style: none none solid;
  border-width: 1px 1px 2px;
  border-color: #000 #000 #fff;
  border-radius: 20px;
  background-color: hsla(0, 0%, 40%, 0.58);
  -webkit-transition: background-color 200ms ease;
  transition: background-color 200ms ease;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-weight: 400;
  letter-spacing: 2px;
  text-decoration: none;
  text-transform: uppercase;
  text-shadow: 0 2px 0 #000;
  white-space: normal;
  background-clip: padding-box;
  -webkit-text-fill-color: inherit;
}

.nav-link-middle:hover {
  background-color: #acacac;
}

.nav-link-mint {
  top: 10px;
  margin-right: 15px;
  padding: 6px 12px;
  border: 1px none #000;
  border-radius: 20px;
  background-color: #03e1ff;
  -webkit-transition: background-color 200ms ease;
  transition: background-color 200ms ease;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-weight: 400;
  letter-spacing: 2px;
  text-decoration: none;
  text-transform: uppercase;
  white-space: normal;
  background-clip: padding-box;
  -webkit-text-fill-color: inherit;
}

.nav-link-mint:hover {
  background-color: #797979;
}

.zoolana-hero {
  position: relative;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.centre-section-home {
  position: relative;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 10;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100vh;
  max-height: none;
  min-height: 100vh;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: transparent;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f07ec8a0616b6a0f3e701_Zoolana-Web.jpg");
  background-position: 50% 100%;
  background-size: cover;
  background-repeat: no-repeat;
}

.zoolana-hero-2 {
  width: 55vw;
}

.section-3 {
  position: absolute;
  left: 0%;
  top: auto;
  right: 0%;
  bottom: 20%;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
}

.social-links {
  margin-right: 25px;
  margin-left: 25px;
}

.mint-connect-wallet-div {
  position: absolute;
  left: auto;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 3000;
  display: none;
  height: 60px;
  margin-top: 15px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: end;
  -webkit-align-items: flex-end;
  -ms-flex-align: end;
  align-items: flex-end;
}

.mint-cw-div {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-right: 0px;
  margin-left: 0px;
}

.nav-menu-3 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}

.navbar-3 {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: auto;
  z-index: 2000;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color: transparent;
}

.nav-link-final {
  height: 100%;
  padding-right: 10px;
  padding-left: 10px;
  background-color: #7b7b7b;
  box-shadow: 0 2px 0 0 #000;
  opacity: 1;
  -webkit-transition: background-color 200ms ease;
  transition: background-color 200ms ease;
  font-family: Futuralt, sans-serif;
  color: #fff;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-shadow: 0 2px 0 #000;
}

.nav-link-final:hover {
  border-bottom: 1px none #49e1ff;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
  background-attachment: scroll;
}

.nav-link-final.w--current {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
  color: #fff;
  text-shadow: 0 2px 0 #000;
}

.nav-link-final-left {
  height: 100%;
  border-bottom-left-radius: 20px;
  background-color: #7b7b7b;
  box-shadow: 0 2px 0 0 #000;
  font-family: Futuralt, sans-serif;
  color: #fff;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-shadow: 0 2px 0 #000;
}

.nav-link-final-left:hover {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
}

.nav-link-final-left.w--current {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
  color: #fff;
}

.nav-link-final-right {
  height: 100%;
  border-bottom-right-radius: 20px;
  background-color: #7b7b7b;
  box-shadow: 0 2px 0 0 #000;
  font-family: Futuralt, sans-serif;
  color: #fff;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-shadow: 0 2px 0 #000;
}

.nav-link-final-right:hover {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
}

.nav-link-final-right.w--current {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
  color: #fff;
}

.body-2 {
  background-color: #1f1f1f;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f601b84f26d820469843c_Zoolana-Web.jpg");
  background-position: 50% 50%;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: scroll;
}

.heading {
  position: absolute;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: auto;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-weight: 400;
  letter-spacing: 2px;
  text-shadow: 4px 4px 0 #000;
}

.paragraph {
  overflow: visible;
  max-height: 50vh;
  font-family: Futuralt, sans-serif;
  color: #bdbdbd;
  font-size: 16px;
  line-height: 20px;
  font-style: normal;
  font-weight: 400;
  text-align: center;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.div-block-2 {
  width: 75%;
}

.whitepaper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  justify-items: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  grid-auto-flow: column;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto auto auto auto auto auto auto;
  grid-template-rows: auto auto auto auto auto auto auto;
}

.image-2 {
  max-width: 75%;
}

.slide {
  position: relative;
  min-height: auto;
  min-width: 100vw;
  padding-right: 100px;
  padding-left: 100px;
  clear: both;
  background-color: transparent;
}

.slider {
  position: relative;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  display: block;
  max-height: none;
  min-height: 100vh;
  padding-top: 120px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-align-content: space-between;
  -ms-flex-line-pack: justify;
  align-content: space-between;
  background-color: transparent;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-position: 0px 0px;
  background-size: cover;
  background-clip: border-box;
  -webkit-text-fill-color: inherit;
}

.story-1 {
  min-height: auto;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-align-content: start;
  -ms-flex-line-pack: start;
  align-content: start;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
  grid-auto-flow: row;
  -ms-grid-columns: 1fr 1.5fr;
  grid-template-columns: 1fr 1.5fr;
  -ms-grid-rows: 10% 90%;
  grid-template-rows: 10% 90%;
}

.story-2 {
  min-height: auto;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-align-content: start;
  -ms-flex-line-pack: start;
  align-content: start;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
  grid-auto-flow: row;
  -ms-grid-columns: 1fr 1.5fr;
  grid-template-columns: 1fr 1.5fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.story-3 {
  min-height: auto;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-align-content: start;
  -ms-flex-line-pack: start;
  align-content: start;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
  grid-auto-flow: row;
  -ms-grid-columns: 1.5fr 1fr;
  grid-template-columns: 1.5fr 1fr;
  -ms-grid-rows: auto;
  grid-template-rows: auto;
}

.section-4 {
  display: none;
}

.link {
  color: #fff;
}

.link-2 {
  color: #fff;
}

.faq {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  justify-items: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  grid-auto-flow: column;
  -ms-grid-columns: 1fr;
  grid-template-columns: 1fr;
  -ms-grid-rows: auto auto auto auto auto auto auto;
  grid-template-rows: auto auto auto auto auto auto auto;
}

.section-5 {
  min-height: 100vh;
}

.slide-nav {
  position: absolute;
  left: 0%;
  top: auto;
  right: 0%;
  bottom: 0%;
  display: block;
}

.html-embed-mobile {
  display: none;
}

.arrow {
  position: absolute;
  left: 0px;
  right: 0px;
  bottom: 30px;
  display: block;
  width: auto;
  height: auto;
  margin-right: auto;
  margin-left: auto;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
}

.section {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: auto;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.section.wide {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: auto;
  padding-top: 10vh;
  padding-bottom: 10vh;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #1b1b1b;
}

.section.wide.img {
  position: relative;
  width: auto;
  height: auto;
  padding-top: 0vh;
  padding-bottom: 10vh;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color: #1f1f1f;
}

.wrap {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-width: 700px;
  margin-top: 0px;
  padding-top: 0px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  text-align: center;
}

.title {
  display: inline-block;
  padding-bottom: 5px;
  border-bottom: 1px none #2e2e2e;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 90%;
  max-width: 1200px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.feature-wrap {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 90vw;
  margin-top: 10vh;
  margin-bottom: 10vh;
  padding-right: 10vw;
  padding-left: 10vw;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-justify-content: space-around;
  -ms-flex-pack: distribute;
  justify-content: space-around;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border: 1px none #000;
}

.feature-wrap.icons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: auto;
  margin-top: 0vh;
  margin-bottom: 0vh;
  padding-right: 0vw;
  padding-left: 0vw;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-flex-wrap: nowrap;
  -ms-flex-wrap: nowrap;
  flex-wrap: nowrap;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
  border-style: none;
  border-radius: 0px;
  background-color: #1f1f1f;
}

.title-2 {
  display: inline-block;
  padding-bottom: 5px;
  border-bottom: 1px none #2e2e2e;
  color: #a8a8a8;
  font-size: 12px;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.black {
  font-family: 'Horizon nmem', sans-serif;
  color: #000;
  font-size: 37px;
  text-transform: none;
}

.feature-content {
  width: 55vw;
  max-width: 500px;
  padding-right: 4vw;
  padding-left: 4vw;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  border: 1px none #000;
  text-align: left;
}

.feature-content.icons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 33.3%;
  height: auto;
  max-width: none;
  padding: 90px 31px 30px 30px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
  background-position: 0px 0px, 50% 50%;
  background-size: auto, cover;
  text-align: center;
}

.feature-image {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 50vw;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border: 1px none #000;
}

.section-2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: auto;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #fff;
  background-image: -webkit-gradient(linear, left bottom, left top, from(#1f1f1f), to(transparent)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-image: linear-gradient(0deg, #1f1f1f, transparent), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-position: 0px 0px, 50% 0%;
  background-size: auto, cover;
  background-repeat: repeat, repeat-y;
}

.h2-white {
  display: block;
  margin-top: 12px;
  margin-bottom: 33px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-transform: none;
}

.paragraph-copy {
  overflow: visible;
  max-height: 50vh;
  font-family: Futuralt, sans-serif;
  color: #000;
  font-size: 16px;
  line-height: 20px;
  font-weight: 400;
  text-align: center;
  text-shadow: 1px 1px 0 #dfdfdf;
  -o-object-fit: fill;
  object-fit: fill;
}

.alpha-edition-paragraph {
  color: #fff;
  text-align: left;
  text-shadow: none;
}

.text-span-2 {
  display: none;
  color: #bdbdbd;
}

.paragraph-2 {
  color: #333;
  font-size: 200px;
  font-weight: 700;
}

.paragraph-3 {
  font-size: 140px;
  font-weight: 700;
}

.paragraph-copy {
  overflow: visible;
  max-height: 50vh;
  font-family: Futuralt, sans-serif;
  color: #989898;
  font-size: 16px;
  line-height: 20px;
  font-weight: 400;
  text-align: left;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.question-mark {
  color: #51c5ff;
  text-align: left;
  text-shadow: none;
}

.feature-content-copy {
  width: 50vw;
  max-width: 450px;
  padding-right: 4vw;
  padding-left: 4vw;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  border: 1px none #000;
  text-align: left;
}

.feature-content-copy.icons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 33.3%;
  max-width: none;
  padding: 90px 30px 30px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f1d4ed17882beef5c075_Beyond%20Reach%20Final.jpeg");
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f1d4ed17882beef5c075_Beyond%20Reach%20Final.jpeg");
  background-position: 0px 0px, 90% 50%;
  background-size: auto, cover;
  text-align: center;
}

.feature-content-copy-2 {
  width: 50vw;
  max-width: 450px;
  padding-right: 4vw;
  padding-left: 4vw;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  border: 1px none #000;
  text-align: left;
}

.feature-content-copy-2.icons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 33.3%;
  max-width: none;
  padding: 90px 30px 30px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f27b8f7da56d3a0da1df_Reclaimed_Tower.jpg");
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f27b8f7da56d3a0da1df_Reclaimed_Tower.jpg");
  background-position: 0px 0px, 80% 50%;
  background-size: auto, cover;
  text-align: center;
}

.white {
  color: #fff;
  font-style: normal;
}

.text-span-3 {
  font-family: Futuralt, sans-serif;
  font-size: 27px;
  font-weight: 400;
}

.image-5 {
  max-width: 80%;
  margin-top: 40px;
}

.h2-choose-your-tribe {
  position: relative;
  left: 0%;
  right: 0%;
  bottom: auto;
  display: block;
  margin-bottom: 0px;
  padding-top: 49px;
  padding-bottom: 25px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-align: center;
  text-transform: none;
}

.h2-zoolana {
  display: block;
  margin-top: 60px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-transform: none;
}

.slider-2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  min-height: 100vh;
  padding: 30px 59px 75px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: transparent;
}

.columns {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.h2-story {
  display: block;
  margin-top: 0px;
  margin-bottom: 27px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-align: center;
  text-transform: none;
}

.paragraph-slider {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: visible;
  max-height: 100vh;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: Futuralt, sans-serif;
  color: #bdbdbd;
  font-size: 16px;
  line-height: 20px;
  font-weight: 400;
  text-align: center;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.image-6 {
  width: auto;
}

.column-2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  max-height: 100%;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
}

.h2-roadmap {
  display: block;
  margin-top: 30px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-transform: none;
}

.grid-2 {
  display: -ms-grid;
  display: grid;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  justify-items: start;
  -webkit-box-align: start;
  -webkit-align-items: start;
  -ms-flex-align: start;
  align-items: start;
  -webkit-align-content: start;
  -ms-flex-line-pack: start;
  align-content: start;
  grid-auto-flow: row;
  grid-auto-columns: 1fr;
  grid-column-gap: 16px;
  grid-row-gap: 16px;
  -ms-grid-columns: 0.25fr 1fr;
  grid-template-columns: 0.25fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
}

.bullet-list {
  overflow: visible;
  max-height: 50vh;
  font-family: Futuralt, sans-serif;
  color: #bdbdbd;
  font-size: 16px;
  line-height: 20px;
  font-style: normal;
  font-weight: 400;
  text-align: left;
  text-decoration: none;
  list-style-type: disc;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.bullet-list-strike {
  display: block;
  overflow: visible;
  max-height: 50vh;
  grid-auto-columns: 1fr;
  -ms-grid-columns: 1fr 1fr;
  grid-template-columns: 1fr 1fr;
  -ms-grid-rows: auto auto;
  grid-template-rows: auto auto;
  font-family: Futuralt, sans-serif;
  color: #bdbdbd;
  font-size: 16px;
  line-height: 20px;
  font-style: normal;
  font-weight: 400;
  text-align: left;
  text-decoration: line-through;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.strikethrough {
  text-decoration: line-through;
}

.q1 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  border-bottom: 1px none #2e2e2e;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  text-align: center;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.footer {
  padding-top: 60px;
  padding-bottom: 40px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  background-color: #000;
  text-align: center;
}

.footer-flex-container {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  margin-bottom: 40px;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  text-align: left;
}

.footer-logo-link {
  max-height: 60px;
  min-width: 60px;
  -webkit-box-flex: 0;
  -webkit-flex: 0 auto;
  -ms-flex: 0 auto;
  flex: 0 auto;
}

.footer-image {
  -o-object-fit: contain;
  object-fit: contain;
  -o-object-position: 0% 50%;
  object-position: 0% 50%;
}

.footer-heading {
  margin-top: 0px;
  margin-bottom: 20px;
  color: #6e6e6e;
  font-size: 14px;
  line-height: 1.5;
}

.footer-link {
  display: block;
  margin-bottom: 10px;
  color: #444;
  text-decoration: none;
}

.footer-link:hover {
  text-decoration: underline;
}

.section-what-is-zoolana {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: auto;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.section-what-is-zoolana.wide {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: auto;
  padding-top: 10vh;
  padding-bottom: 10vh;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #1b1b1b;
}

.section-what-is-zoolana.wide.img {
  position: relative;
  width: auto;
  height: auto;
  padding-top: 0vh;
  padding-bottom: 0vh;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color: #1f1f1f;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176e8a9425fde5a9ccc2359_background.png");
  background-position: 50% 0%;
  background-size: cover;
  background-repeat: no-repeat;
}

.chooseyourtribe {
  height: 0px;
}

.storysection {
  height: 0px;
}

.roadmapsection {
  height: 0px;
}

.image-7 {
  margin-bottom: 20px;
}

.text-span-4 {
  display: inline-block;
  font-size: 300px;
}

.red-text {
  color: red;
}

.blue-text {
  color: #48e0f2;
}

.roadmap-section {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: auto;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}

.roadmap-section.wide {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: auto;
  padding-top: 10vh;
  padding-bottom: 10vh;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: #1b1b1b;
}

.roadmap-section.wide.img {
  position: relative;
  width: auto;
  height: auto;
  padding-top: 0vh;
  padding-bottom: 10vh;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color: #1f1f1f;
  background-image: -webkit-gradient(linear, left top, left bottom, from(transparent), color-stop(10%, #1f1f1f));
  background-image: linear-gradient(180deg, transparent, #1f1f1f 10%);
}

.alpha-line {
  margin-bottom: 51px;
}

.alpha-para {
  overflow: visible;
  max-height: 50vh;
  font-family: Futuralt, sans-serif;
  color: #cfcfcf;
  font-size: 16px;
  line-height: 20px;
  font-weight: 400;
  text-align: left;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.alpha-text {
  overflow: visible;
  max-height: 50vh;
  font-family: Futuralt, sans-serif;
  color: #cecece;
  font-size: 16px;
  line-height: 20px;
  font-style: normal;
  font-weight: 400;
  text-align: center;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.grid-3 {
  display: none;
  justify-items: start;
  grid-auto-flow: column;
  -ms-grid-columns: 2fr 2fr 2fr;
  grid-template-columns: 2fr 2fr 2fr;
  -ms-grid-rows: auto auto auto auto auto auto auto auto auto auto;
  grid-template-rows: auto auto auto auto auto auto auto auto auto auto;
  border: 1px none #000;
  border-radius: 2px;
}

.h2access {
  display: block;
  margin-top: 60px;
  margin-left: 38px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-transform: none;
}

.h2-alpha {
  display: block;
  margin-top: 60px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 37px;
  text-align: left;
  text-transform: none;
}

.alpha-bullet {
  overflow: visible;
  max-height: 50vh;
  border-bottom: 1px none #686868;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-size: 16px;
  line-height: 20px;
  font-style: normal;
  font-weight: 400;
  text-align: left;
  text-decoration: none;
  list-style-type: none;
  text-shadow: 2px 2px 0 #000;
  -o-object-fit: fill;
  object-fit: fill;
}

.section-6 {
  height: 3px;
  background-image: linear-gradient(277deg, #cd1fed, #37bb78 53%, #47ddef);
}

.tribe-section {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: visible;
  width: auto;
  -o-object-fit: contain;
  object-fit: contain;
}

.feature-content-table {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 50vw;
  max-width: none;
  padding-right: 4vw;
  padding-left: 4vw;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  border: 1px none #000;
  text-align: left;
}

.feature-content-table.icons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 33.3%;
  height: auto;
  max-width: none;
  padding: 90px 31px 30px 30px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
  background-position: 0px 0px, 50% 50%;
  background-size: auto, cover;
  text-align: center;
}

.title-centre {
  display: inline-block;
  margin-top: 16px;
  padding-bottom: 5px;
  border-bottom: 1px none #2e2e2e;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  text-align: center;
  letter-spacing: 2px;
  text-transform: uppercase;
}

.video {
  height: 100%;
}

.background-video {
  width: 100vw;
  height: 100vh;
}

.explore {
  z-index: 10;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100vh;
  max-height: none;
  min-height: 100vh;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-align-content: center;
  -ms-flex-line-pack: center;
  align-content: center;
  background-color: transparent;
}

.exploreworld {
  position: relative;
  left: 0%;
  top: 34%;
  right: 0%;
  bottom: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}

.explorepara {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-bottom: 1px none #2e2e2e;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-shadow: 1px 1px 6px #000;
}

.background-video-2 {
  position: absolute;
  width: 33.3%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.explorelink {
  top: 10px;
  margin-right: 0px;
  padding: 5px 20px;
  border-style: none none solid;
  border-width: 1px 1px 2px;
  border-color: #000 #000 #fff;
  border-radius: 20px;
  background-color: hsla(0, 0%, 40%, 0.58);
  -webkit-transition: background-color 200ms ease;
  transition: background-color 200ms ease;
  font-family: Futuralt, sans-serif;
  color: #fff;
  font-weight: 400;
  letter-spacing: 2px;
  text-decoration: none;
  text-transform: uppercase;
  text-shadow: 0 2px 0 #000;
  white-space: normal;
  background-clip: padding-box;
  -webkit-text-fill-color: inherit;
}

.explorelink:hover {
  background-color: #acacac;
}

.background-video-3 {
  width: 34%;
  height: auto;
}

.background-video-3.video {
  width: 33.3vw;
  height: auto;
}

.feature-content-test {
  width: 55vw;
  max-width: 500px;
  padding-right: 4vw;
  padding-left: 4vw;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  border: 1px none #000;
  text-align: left;
}

.feature-content-test.icons {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  max-width: none;
  padding: 90px 31px 30px 30px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -webkit-justify-content: flex-start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.5)), to(rgba(0, 0, 0, 0.5)));
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));
  text-align: center;
}

.div-block-3 {
  background-image: -webkit-gradient(linear, left top, left bottom, from(#1f1f1f), color-stop(18%, transparent)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-image: linear-gradient(180deg, #1f1f1f, transparent 18%), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-position: 0px 0px, 50% 100%;
  background-size: auto, cover;
}

.marketplace {
  position: relative;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 10;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100vh;
  max-height: none;
  min-height: 100vh;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: transparent;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-position: 50% 100%;
  background-size: cover;
  background-repeat: no-repeat;
}

.div-block-4 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 700px;
  height: 700px;
  padding: 40px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: justify;
  -webkit-justify-content: space-between;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-radius: 17px;
  background-color: #292929;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176dba47f254124db2ade8e_background60.jpg");
  background-position: 0px 0px;
  background-size: cover;
  background-repeat: no-repeat;
  box-shadow: 0 7px 20px 0 rgba(0, 0, 0, 0.84);
}

.background-video-4 {
  z-index: 100;
  width: 100%;
  height: 500px;
  margin-bottom: 15px;
  border-style: solid;
  border-width: 3px;
  border-color: #a7a7a7;
  border-radius: 7px;
}

.text-span-5 {
  text-align: center;
}

.h2-mint {
  display: block;
  margin-top: 0px;
  -webkit-box-align: start;
  -webkit-align-items: flex-start;
  -ms-flex-align: start;
  align-items: flex-start;
  font-family: 'Horizon nmem', sans-serif;
  color: #fff;
  font-size: 34px;
  text-align: center;
  text-transform: none;
}

.text-span-6 {
  border: 1px solid transparent;
  color: red;
}

.centre-section-mint {
  position: relative;
  left: 0%;
  top: 0%;
  right: 0%;
  bottom: 0%;
  z-index: 10;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100vh;
  max-height: none;
  min-height: 100vh;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  background-color: transparent;
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f07ec8a0616b6a0f3e701_Zoolana-Web.jpg");
  background-position: 50% 100%;
  background-size: cover;
  background-repeat: no-repeat;
}

.navbar-4 {
  position: absolute;
  left: 9%;
  top: 0%;
  right: auto;
  bottom: auto;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  background-color: transparent;
}

.nav-link-mint-page {
  height: 100%;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
  background-color: #7b7b7b;
  box-shadow: 0 2px 0 0 #000;
  font-family: Futuralt, sans-serif;
  color: #fff;
  letter-spacing: 2px;
  text-transform: uppercase;
  text-shadow: 0 2px 0 #000;
}

.nav-link-mint-page:hover {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
}

.nav-link-mint-page.w--current {
  background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f54fbd12f659585305d15_navbar%20gradient.png");
  background-position: 50% 100%;
  background-size: 70px 2px;
  background-repeat: no-repeat;
  color: #fff;
}

@media screen and (max-width: 991px) {
  .body {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .nav-link {
    display: none;
    margin-right: 10px;
    margin-left: 10px;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }

  .nav-link-mint {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin-right: 10px;
    margin-left: 10px;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }

  .centre-section-home {
    left: 0%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    padding-top: 108px;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .zoolana-hero-2 {
    width: 75vw;
  }

  .section-3 {
    position: relative;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: end;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }

  .mint-connect-wallet-div {
    position: absolute;
    left: 0%;
    top: 10vh;
    right: 0%;
    bottom: 0%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin-top: 0%;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    align-self: auto;
    -webkit-box-ordinal-group: 1;
    -webkit-order: 0;
    -ms-flex-order: 0;
    order: 0;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
  }

  .mint-cw-div {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    -webkit-align-content: flex-start;
    -ms-flex-line-pack: start;
    align-content: flex-start;
  }

  .body-2 {
    background-color: #1f1f1f;
    background-image: url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f601b84f26d820469843c_Zoolana-Web.jpg");
    background-size: auto 100vh;
    background-repeat: repeat-x;
  }

  .heading {
    position: relative;
    margin-top: 23px;
    margin-bottom: 31px;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .paragraph {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    font-size: 14px;
  }

  .div-block-2 {
    margin-top: -400px;
  }

  .whitepaper {
    margin-top: 481px;
    grid-auto-flow: column;
  }

  .image-2 {
    max-width: 98%;
  }

  .slider {
    display: none;
    overflow: visible;
  }

  .section-4 {
    position: absolute;
    left: 0%;
    top: 15%;
    right: 0%;
    bottom: 0%;
    display: block;
  }

  .image-3 {
    position: relative;
    display: inline-block;
    margin-top: 20px;
    margin-bottom: 20px;
    clear: none;
    -webkit-align-self: center;
    -ms-flex-item-align: center;
    -ms-grid-row-align: center;
    align-self: center;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .container {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .faq {
    margin-top: 481px;
    grid-auto-flow: column;
  }

  .feature-wrap {
    margin-top: 5vh;
    margin-bottom: 5vh;
    padding-right: 0vw;
    padding-left: 0vw;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
  }

  .title-2 {
    display: block;
    text-align: center;
  }

  .feature-content {
    width: auto;
  }

  .paragraph-copy {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .paragraph-copy {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .h2-choose-your-tribe {
    margin-top: 32px;
  }

  .h2-story {
    margin-bottom: 8px;
  }

  .paragraph-slider {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    font-size: 14px;
  }

  .grid-2 {
    -webkit-box-align: start;
    -webkit-align-items: start;
    -ms-flex-align: start;
    align-items: start;
    -webkit-align-content: start;
    -ms-flex-line-pack: start;
    align-content: start;
  }

  .bullet-list {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    font-size: 14px;
  }

  .bullet-list-strike {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .footer {
    padding-right: 20px;
    padding-left: 20px;
  }

  .alpha-para {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }

  .alpha-text {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    font-size: 14px;
  }

  .h2-alpha {
    text-align: center;
  }

  .alpha-bullet {
    position: relative;
    display: block;
    -webkit-align-self: flex-start;
    -ms-flex-item-align: start;
    align-self: flex-start;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    font-size: 14px;
  }

  .feature-content-table {
    width: auto;
  }

  .explore {
    left: 0%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    padding-top: 108px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .exploreworld {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: end;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }

  .feature-content-test {
    width: auto;
  }

  .marketplace {
    left: 0%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    padding-top: 108px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .h2-mint {
    text-align: center;
  }

  .centre-section-mint {
    left: 0%;
    top: 0%;
    right: 0%;
    bottom: 0%;
    padding-top: 108px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .navbar-4 {
    left: 4%;
    top: 0%;
    right: auto;
    bottom: auto;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }

  .nav-link-mint-page {
    position: relative;
    left: 0%;
    top: 0%;
    right: auto;
    bottom: auto;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }
}

@media screen and (max-width: 767px) {
  .centre-section-home {
    width: auto;
    padding-top: 222px;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .zoolana-hero-2 {
    width: 85vw;
  }

  .section-3 {
    position: absolute;
    left: 0%;
    top: auto;
    right: 0%;
    bottom: 20%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .mint-connect-wallet-div {
    top: 3px;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }

  .mint-cw-div {
    -o-object-fit: fill;
    object-fit: fill;
  }

  .nav-menu-3 {
    background-color: transparent;
  }

  .navbar-3 {
    display: block;
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }

  .nav-link-final {
    height: auto;
    text-align: center;
  }

  .menu-button {
    background-color: transparent;
  }

  .menu-button:active {
    background-color: #7b7b7b;
  }

  .menu-button.w--open {
    background-color: #7b7b7b;
  }

  .nav-link-final-left {
    height: auto;
    border-bottom-left-radius: 0px;
    text-align: center;
  }

  .nav-link-final-right {
    height: auto;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 0px;
    text-align: center;
  }

  .heading {
    font-size: 30px;
  }

  .paragraph {
    max-height: none;
  }

  .div-block-2 {
    margin-top: -778px;
  }

  .whitepaper {
    margin-top: 595px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
    -ms-grid-rows: auto auto;
    grid-template-rows: auto auto;
  }

  .image-2 {
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    -ms-grid-row-align: auto;
    align-self: auto;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
  }

  .section-4 {
    margin-top: -61px;
    padding-right: 22px;
    padding-left: 22px;
  }

  .html-embed {
    display: none;
    max-width: 640vw;
  }

  .faq {
    margin-top: 595px;
    -ms-grid-columns: 1fr;
    grid-template-columns: 1fr;
    -ms-grid-rows: auto auto;
    grid-template-rows: auto auto;
  }

  .html-embed-mobile {
    display: block;
    max-width: 640vw;
  }

  .wrap {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    width: 100%;
    max-width: none;
    padding-right: 15vw;
    padding-left: 15vw;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .feature-wrap {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .feature-wrap.icons {
    display: block;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    -webkit-flex-direction: row;
    -ms-flex-direction: row;
    flex-direction: row;
    -webkit-flex-wrap: wrap;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }

  .feature-content.icons {
    width: auto;
    padding-right: 30px;
    padding-bottom: 30px;
    padding-left: 30px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: left;
  }

  .paragraph-copy {
    max-height: none;
  }

  .paragraph-copy {
    max-height: none;
  }

  .feature-content-copy.icons {
    width: auto;
    padding-right: 30px;
    padding-bottom: 30px;
    padding-left: 30px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: left;
  }

  .feature-content-copy-2.icons {
    width: auto;
    padding-right: 30px;
    padding-bottom: 30px;
    padding-left: 30px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: left;
  }

  .image-5 {
    margin-top: 32px;
    margin-bottom: 32px;
  }

  .slider-2 {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    height: auto;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .columns {
    height: auto;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-box-pack: justify;
    -webkit-justify-content: space-between;
    -ms-flex-pack: justify;
    justify-content: space-between;
  }

  .paragraph-slider {
    max-height: none;
  }

  .image-6 {
    margin-top: 15px;
    margin-bottom: 15px;
  }

  .slide-final {
    height: auto;
  }

  .bullet-list {
    max-height: none;
  }

  .bullet-list-strike {
    max-height: none;
  }

  .footer {
    padding: 40px 20px;
  }

  .footer-image {
    -o-object-fit: contain;
    object-fit: contain;
  }

  .image-8 {
    margin-top: 15px;
    margin-bottom: 15px;
  }

  .image-9 {
    margin-top: 15px;
    margin-bottom: 15px;
  }

  .alpha-para {
    max-height: none;
  }

  .alpha-text {
    max-height: none;
  }

  .alpha-bullet {
    max-height: none;
  }

  .tribe-section {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .feature-content-table.icons {
    width: auto;
    padding-right: 30px;
    padding-bottom: 30px;
    padding-left: 30px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: left;
  }

  .background-video {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .explore {
    width: auto;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .exploreworld {
    position: absolute;
    left: 0%;
    top: auto;
    right: 0%;
    bottom: 20%;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .background-video-3 {
    width: 100%;
  }

  .background-video-3.video {
    width: 100vw;
  }

  .feature-content-test.icons {
    width: auto;
    padding-right: 30px;
    padding-bottom: 30px;
    padding-left: 30px;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    text-align: left;
  }

  .marketplace {
    width: auto;
    padding-top: 222px;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .centre-section-mint {
    width: auto;
    padding-top: 222px;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .nav-link-mint-page {
    height: auto;
    border-bottom-left-radius: 20px;
    text-align: center;
  }
}

@media screen and (max-width: 479px) {
  .nav-link {
    text-align: center;
  }

  .nav-link-mint {
    padding-top: 15px;
    padding-bottom: 15px;
  }

  .zoolana-hero {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    margin-top: 35px;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    align-self: auto;
  }

  .centre-section-home {
    position: relative;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .zoolana-hero-2 {
    width: 100vw;
  }

  .section-3 {
    left: 0%;
    top: auto;
    right: 0%;
    bottom: -10%;
    margin-bottom: 250px;
    -webkit-box-align: end;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }

  .mint-connect-wallet-div {
    top: 40px;
    z-index: 4000;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }

  .mint-cw-div {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: stretch;
    -webkit-align-items: stretch;
    -ms-flex-align: stretch;
    align-items: stretch;
  }

  .nav-link-final {
    height: auto;
  }

  .nav-link-final-left {
    height: auto;
  }

  .nav-link-final-right {
    height: auto;
  }

  .div-block-2 {
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    -ms-grid-row-align: auto;
    align-self: auto;
  }

  .image-2 {
    max-width: 95%;
    -webkit-align-self: auto;
    -ms-flex-item-align: auto;
    -ms-grid-row-align: auto;
    align-self: auto;
  }

  .section-4 {
    margin-top: -25px;
  }

  .wrap {
    margin-top: 0px;
    padding-right: 5vw;
    padding-left: 5vw;
  }

  .feature-wrap {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .black {
    font-size: 26px;
  }

  .feature-content {
    width: auto;
  }

  .feature-content.icons {
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.8)), to(rgba(0, 0, 0, 0.8))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
    background-position: 0px 0px, 50% 50%;
    background-size: auto, cover;
  }

  .feature-image {
    width: auto;
    margin-top: -41px;
    margin-bottom: 30px;
  }

  .section-2 {
    padding-bottom: 28px;
  }

  .h2-white {
    font-size: 26px;
  }

  .paragraph-2 {
    margin-bottom: -30px;
  }

  .question-mark {
    display: block;
    font-size: 150px;
  }

  .feature-content-copy {
    width: auto;
  }

  .feature-content-copy.icons {
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.8)), to(rgba(0, 0, 0, 0.8))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f1d4ed17882beef5c075_Beyond%20Reach%20Final.jpeg");
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f1d4ed17882beef5c075_Beyond%20Reach%20Final.jpeg");
    background-position: 0px 0px, 90% 50%;
    background-size: auto, cover;
  }

  .feature-content-copy-2 {
    width: auto;
  }

  .feature-content-copy-2.icons {
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.8)), to(rgba(0, 0, 0, 0.8))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f27b8f7da56d3a0da1df_Reclaimed_Tower.jpg");
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f27b8f7da56d3a0da1df_Reclaimed_Tower.jpg");
    background-position: 0px 0px, 80% 50%;
    background-size: auto, cover;
  }

  .image-5 {
    max-width: 100%;
  }

  .h2-choose-your-tribe {
    font-size: 26px;
  }

  .h2-zoolana {
    font-size: 26px;
  }

  .columns {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .h2-story {
    font-size: 26px;
  }

  .h2-roadmap {
    font-size: 26px;
  }

  .footer {
    padding-right: 20px;
    padding-left: 20px;
    text-align: left;
  }

  .footer-flex-container {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }

  .footer-logo-link {
    height: 60px;
  }

  .footer-heading {
    margin-top: 20px;
  }

  .roadmap-section.wide.img {
    -webkit-box-pack: start;
    -webkit-justify-content: flex-start;
    -ms-flex-pack: start;
    justify-content: flex-start;
  }
  <a href="http://alpha.zoolana.io" class="nav-link-mint">mint</a>
  .grid-3 {
    grid-column-gap: 0px;
  }

  .h2access {
    font-size: 26px;
  }

  .h2-alpha {
    font-size: 26px;
  }

  .feature-content-table {
    width: auto;
  }

  .feature-content-table.icons {
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.8)), to(rgba(0, 0, 0, 0.8))), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url("https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176f18fa4e37b4ec1aed9f3_Highland%20Mesa%20Final.jpeg");
    background-position: 0px 0px, 50% 50%;
    background-size: auto, cover;
  }

  .background-video {
    padding-bottom: 120px;
  }

  .explore {
    position: relative;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
  }

  .exploreworld {
    left: 0%;
    top: auto;
    right: 0%;
    bottom: -10%;
    margin-bottom: 250px;
    -webkit-box-align: end;
    -webkit-align-items: flex-end;
    -ms-flex-align: end;
    align-items: flex-end;
  }

  .feature-content-test {
    width: auto;
  }

  .feature-content-test.icons {
    background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(0, 0, 0, 0.51)), to(rgba(0, 0, 0, 0.51)));
    background-image: linear-gradient(180deg, rgba(0, 0, 0, 0.51), rgba(0, 0, 0, 0.51));
  }

  .marketplace {
    position: relative;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
  }

  .div-block-4 {
    height: auto;
    margin-top: 7px;
    margin-right: 16px;
    margin-left: 16px;
  }

  .background-video-4 {
    height: 200px;
    max-height: 200px;
  }

  .h2-mint {
    font-size: 26px;
  }

  .centre-section-mint {
    position: relative;
    height: 110vh;
    max-height: none;
    min-height: 1000px;
    padding-top: 61px;
    -webkit-box-align: start;
    -webkit-align-items: flex-start;
    -ms-flex-align: start;
    align-items: flex-start;
    background-size: auto;
    background-repeat: repeat-y;
  }

  .nav-link-mint-page {
    height: auto;
  }
}

#w-node-a0fddfdf-25b0-bc31-3c3d-da6d9fb703de-3aadbb21 {
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
}

#w-node-ff87d785-9029-d3c7-c442-94fa5f03258e-3aadbb21 {
  -ms-grid-row: span 1;
  grid-row-start: span 1;
  -ms-grid-row-span: 1;
  grid-row-end: span 1;
  -ms-grid-column: span 1;
  grid-column-start: span 1;
  -ms-grid-column-span: 1;
  grid-column-end: span 1;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58c2ba39c800737c32_FuturaLT-Bold.ttf') format('truetype'), url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b5837dd2e3ea7e2405f_FuturaLT-CondExtraBoldObl.ttf') format('truetype'), url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58e7186a2027966c38_FuturaLT-ExtraBold.ttf') format('truetype');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt book';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58492c2d3d55666c71_FuturaLT-Book.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt condensed';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b588a06160150f4082d_FuturaLT-Condensed.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58bd291065c7824bb1_FuturaLT-BookOblique.ttf') format('truetype'), url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58cbae1db9b0aa0bb8_FuturaLT-Oblique.ttf') format('truetype');
  font-weight: 400;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt Condensed';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b5802cb88f197d13222_FuturaLT-CondensedBoldOblique.ttf') format('truetype');
  font-weight: 700;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt Condensed';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58858fa4c20ed2bd8b_FuturaLT-CondensedBold.ttf') format('truetype'), url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b59353d041831ef2613_FuturaLT-CondensedExtraBold.ttf') format('truetype');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b584e78501af95cca02_FuturaLT-BoldOblique.ttf') format('truetype'), url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b582067e91a3a3c3dc2_FuturaLT-ExtraBoldOblique.ttf') format('truetype');
  font-weight: 700;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt Condensed';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b5838a8e17e88f8da49_FuturaLT-CondensedLight.ttf') format('truetype'), url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58e7186a1305966c39_FuturaLT-CondensedLightObl.ttf') format('truetype');
  font-weight: 300;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt Condensed';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b5802cb8865f0d13223_FuturaLT-CondensedOblique.ttf') format('truetype');
  font-weight: 400;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58858fa4ab92d2bd8c_FuturaLT-Heavy.ttf') format('truetype');
  font-weight: 900;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b586cd85cd238ef6d85_FuturaLT-HeavyOblique.ttf') format('truetype');
  font-weight: 900;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58cff69a3a386cbfd0_FuturaLT-Light.ttf') format('truetype');
  font-weight: 300;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b58a19dee2718d4eb5b_FuturaLT-LightOblique.ttf') format('truetype');
  font-weight: 300;
  font-style: italic;
  font-display: swap;
}
@font-face {
  font-family: 'Futuralt';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/616f0b596385fedb54d96401_FuturaLT.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
@font-face {
  font-family: 'Horizon nmem';
  src: url('https://uploads-ssl.webflow.com/616d8cf9ec276c1e79adbb20/6176cb410173cc25786d2f83_Horizon-nMeM.ttf') format('truetype');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}
