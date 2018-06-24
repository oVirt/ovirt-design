# VM Portal

We are taking a fresh look at VM Portal with the UXD team. These are the designs under review.

## Login
Login will be updated as a separate RFE from this project. It will likely use the patternfly-react component under development.
[Bug 1549486 – [RFE] update login page to match new PatternFly login design](https://bugzilla.redhat.com/show_bug.cgi?id=1549486)

![login](img/login.png)

## Edit VM
The Edit VM flow will transition from a dialog-ish page view to an inline-edit dashboard.

First version:
![edit_vm_inline.png](img/edit_vm_inline.png)

We do not have in/out network stats for VMs at the moment, only total bandwidth.

Second version:

![edit_vm_inline_v2](img/edit_vm_inline_v2.png)

Active edit mode:

![edit_vm_inline_v2_active](img/edit_vm_inline_v2_active.png)

## VM List
The page was streamlined and polished. 'Other OS' VMs have a new icon to replace the '?', which was confusing.

Old:

![question_icons](img/question_icons.png)

Machine icon:

![generic_os_machine](img/generic_os_machine.png)


Team prefers the 'Other OS' software icon, but will gray its color:

![generic_os_other](img/generic_os_other.png)

With the notification drawer:

![other_os_with_drawer](img/other_os_with_drawer.png)

VMs selector:

![vm_selector_v2](img/vm_selector_v2.png)
