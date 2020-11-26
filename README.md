# MAD_IV_list

Sorting is done by <br>
1. gamepress ranking
2. generation desc

## Preparation

1. Install MAD_IV_list ``git clone https://github.com/dkmur/MAD_IV_list.git``
2. Copy the file `config.example` to `config` and open it in an editor and replace the proper MADmin URL, IV list ID, username, and password.

To get the actual IV list ID, go to your MADmins IV settings page, click on the list's edit button and check your browser's address bar for the numeric value at the end of the URL.

IMPORTANT: Do not add any spaces before or after the `=` characters in the config file.

## Usage

Running `./update` will just upload the latest IV list to your MADmin.

If you want to upload a specific older version of the IV list, just pass the name as parameter such as: <br>`./update ivlist_2020-03-26`

## Support for multiple MAD instances

If you have multple instances, just create multiple config files and pass the name of the config file like this: <br>`./update -c config-instance1 ivlist_2020-03-26`

## History

11-02-2020 Added audino and alomomola <br>
26-03-2020 Added Solosis, Duosion, Reuniclus, Gothita, Duosion and Reuniclus <br>
01-04-2020 Added Stunfisk <br>
21-04-2020 Added Woobat <br>
22-04-2020 Added Stunfisk <br>
06-05-2020 Added Scraggy and adapted order of mons <br>
03-07-2020 Added Ducklett <br>
17-07-2020 Added Petilil <br>
07-08-2020 Added Elgyem <br>
14-08-2020 Added Sewaddle, Cottonee, Emolga <br>
09-10-2020 Added Deerling <br>
26-11-2020 Added generation 6 + remaining pokes other generation not in game/wild. Unsorted at the end of list
