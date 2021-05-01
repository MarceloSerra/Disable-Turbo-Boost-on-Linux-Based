## How to Use

##### Clone the repo:
`git clone https://github.com/MarceloSerra/Disable-Turbo-Boost-on-Linux`

Go to the folder, extract and execute chmod inside to give permissions (_*_ will give permissions to all files in the folder, but you can set to one file just changing _*_ by file name):
`chmod +x *`

Now it's necessary to verify if you've got an intel scaling driver (**intel_pstate**) output:

`sudo ./verify_intel_scaling_driver`

 If the output was (**intel_pstate**), you can continue and execute:

`sudo ./set_turbo_boost_off`

You can check the status by executing (_0_ output = ENABLED and _1_ output = DISABLED):

`sudo ./verify_turbo_boost_status`

You can also re-enable the Turbo Boost by executing:

`sudo ./set_turbo_boost_on`

# That's all!