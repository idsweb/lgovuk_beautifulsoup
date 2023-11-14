# Components used in markup

## Pages
Sample pages where an instance of the component can be found listed below.

### Making a noise complaint
1. Journey page

### Report fly tipping
1. Panel
1. Information block
1. Highlighted information block
1. External link button

### Reprot graffiti
1. Accordian

### Report antisocial behaviour
This contains an information block
***
# Components
## Journey control

## Information block
```html
    <div role="note" aria-label="Information" class="text-highlight text-highlight--red"> If you've been a victim of
        crime you should report this to the police on&nbsp;101, or 999 if it's&nbsp;an emergency.<br>
    </div>
```
These can be highlighted with a class `text-highlight--red` or plain using `text-highlight`.

## Panel
Text is emphasised in panels

### Selector
| tag | selector | value |
|-----|----------|-------|
| div | class    | panel panel-border |

```html
    <div class="panel panel-border">
        <h3>What we're not able to do<br></h3>
        <p>We will not be able to:<br></p>
        <ul class="list list-bullet">
            <li>guarantee the outcome of any investigation<br></li>
            <li>provide you with alternative accommodation (except in very serious circumstances)<br></li>
            <li>keep a case open when no further action is possible<br></li>
            <li>take action for everyday disagreements, such as parking disputes, boundary disputes, untidy gardens<br>
            </li>
        </ul>
    </div>
```

## External link button

### Selector
| tag | selector | value |
|-----|----------|-------|
| a | class    | btn btn-primary btn-arrow |

```html
    <a rel="external" class="btn btn-primary btn-arrow" href="https://services.leeds.gov.uk/FlyTipping"> Report waste on
        public land<span class="sr-only"> External link</span>
    </a>
```

## Accordian

### Selector
| tag | selector | value |
|-----|----------|-------|
| div | class    | accordian |

```html
    <div class="accordion" data-aria-accordion="true" data-multi="true" data-default="none" id="acc_7291">
        <h3 class="accordion__heading"><button type="button" aria-controls="acc_7291_panel_1"
                id="acc_7291_panel_1_trigger" class="accordion__trigger" aria-expanded="false" data-current="false">
                Phone boxes</button></h3>
        <div class="accordion__panel" id="acc_7291_panel_1" aria-hidden="true">
            <p>
                <a href="https://btbusiness.custhelp.com/app/answers/detail/a_id/30231/~/bt-faults:-how-to-report-payphone-faults-or-damage/c/5128/"
                    rel="external">Report graffiti on a phone box to BT</a>.<br>
            </p>
            <p></p>
        </div>
        <h3 class="accordion__heading"><button type="button" aria-controls="acc_7291_panel_2"
                id="acc_7291_panel_2_trigger" class="accordion__trigger" aria-expanded="false" data-current="false"> Bus
                stops, signs and stations </button></h3>
        <div class="accordion__panel" id="acc_7291_panel_2">
            <p>
                <a href="https://westyorks-ca-self.achieveservice.com/en/AchieveForms/?form_uri=sandbox-publish://AF-Process-c597da6f-0515-4b43-8f1a-c50f132cdb25/AF-Stage-76db5d3b-eee7-4783-9ec8-3000fa7d6b14/definition.json&amp;redirectlink=/en&amp;cancelRedirectLink=/en"
                    rel="external">Report graffiti on a bus shelter to West Yorkshire Combined Authority<span
                        class="sr-only"> External link</span></a>.&nbsp;&nbsp;&nbsp;&nbsp;
            </p>
        </div>
    </div>
```