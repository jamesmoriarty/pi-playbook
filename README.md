Raspberry Pi
------------

    ansible-playbook -i hosts server.yml

You must provide a var file.

    ---
    # vars/main.yml
    user: someone
    password: something
    storage_path: /media/usb0
    client_id: xxxxxxxxxxxxx
    api_key: xxxxxxxxxxxxx


Vagrant
-------

    vagrant up
    vagrant provision

