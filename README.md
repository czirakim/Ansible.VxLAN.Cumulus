<snippet>
  <content>

## Ansible.VxLAN.Cumulus

The scope of this project is to automate the deployment of vxlan's on Cumulus switches,
<br>and use evpn as a control-plane mechanism.

##Usage

For adding vlans,spine switches or leaf you need to edit the var files.
<br>And that's it. Also you can use tags an run only the task that you need.
<br>For example if you create a new vxlan for a new vlan, you only have to edit the
<br> group_vars/leaf/vars file to add a new vlan. And run the leaf.yml file
<br> with the tag for the vxlan task only.
<br> like this : ansible-playbook leaf.yml -i inventory -vv  --tags "vxlan"  

## Files
Beside the yml files, the project also includes the GNS3 zip file.

## Credits
This was written by Mihai Cziraki
</content>
</snippet>
