# Backing up your system if you executed: 
`sudo dd if=/dev/zero of=/dev/sda` or `sudo rm -rf /*`. **Also, DONT execute these commands.**

# First method
> Note: this tutorial is Windows only.
> Also, this requires Windows installed on another machine.

## Open a admin command prompt 🎈

- Opening `diskpart`

- Listing disks `lis dis`

## Check what is the lost disk ⭐

- selecting `sel dis 0`

- convert `convert gpt`

- create as primary `create partition primary`

- formatting `format fs=ntfs quick`

- assigning `assign letter e`

## Now look on file explorer 🎉

# Second Method (easier)
> Note: this tutorial is Windows only.

## Open admin command prompt
- `diskpart`
- `list disk`
- `select disk <what is your messed ssd disk number>`
- `clean all`

- Go into Partition Manager on Windows
- Right Click on the unallocated part
- Click on New
- make your own changes

Done! your disk was saved!
