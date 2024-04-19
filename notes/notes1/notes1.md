# Notes 1: Bash Shell

Commands cover in lecture:

## Echo
### Definition:
Display a line of text
### Usage
`echo` + `option` + `string`
### Examples:
* Display a line of text without the new line
  * `echo -n "hello world"`
* Display a line of text that includes a horizontal tab
  * `echo -e "\thello world"`
* Display 2 lines of text in a single echo command
  * `echo -e "Line 1\nLine2"`
* Display 2 lines of text in a single echo command, with the second line starting with a tab
  * `echo -e "Line 1\n\tLine 2"`
* Display 2 lines of text in a single echo command that starts with a tab
  * `echo -e "\tLine 1\tLine 2"`

<hr>

## date
### Definition
Print or set the system date and time
### Usage
`data` + `option`
### Examples
* Display current date
  * `date`
* Display current date in rfc 5322 format
  * `date -R`

