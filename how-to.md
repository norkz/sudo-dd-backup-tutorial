- open a admin command prompt

- `diskpart`

- `lis dis`

Check what is the lost disk

- put `sel dis 0`

- `convert gpt`

- then `create partition primary`

- and then `format fs=ntfs quick`

- now `assign letter e`

- now look in file explorer
