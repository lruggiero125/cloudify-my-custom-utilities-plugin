##Custom Plugin install guide
* pip3 install wagon
* cd cloudify-my-custom-utilities-plugin
* wagon create -v -f -a '--no-cache-dir -c constraints.txt' .
* wagon install cloudify_my_custom_utilities-1.0-py36-none-any.wgn
* cfy plugins upload cloudify_my_custom_utilities-1.0-py36-none-any.wgn -y plugin.yaml -t oss_dev