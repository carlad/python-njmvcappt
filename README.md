Pre-Requisites:
Install Python and its required libraries

If you want to search for appointment only on specific locations say Lawrenceville and Camden, then update the location_arr and locationname_arr variables
location_arr = ['101','104']
locationname_arr = ['Lawrenceville','Camden']

If you want to be notified only when an appointment is available on specific month, for example only on "April" then update the required months variable accordingly.
required_months = ['April']

#For Linux Users:#
Use python3 as you'll run into issues installing/importing dependencies.
Install BeautifulSoup:
`pip3 install BeautifulSoup4`

The `lxml` library is required by BeautifulSoup for parsing:
`pip3 install lxml`

For some reason Ubuntu 20.04 no longer makes a beep noise with `beep`.
One can use `spd-say` instead, eg `os.system('spd-say %s' % "beep")`. It's a little hacky but it works.