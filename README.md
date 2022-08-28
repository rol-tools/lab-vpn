# Lab VPN (coming soon)
Use this to quickly spin up a vpn in the lab environment.

**Why:**

- Triple productivity and save on lab hours by bypassing the lag and latency that comes with using the lab environment through a vnc viewer in the browser.


## Usage

1. From your workstation node clone this repo.

	```
	[student@workstation ~]$ git clone https://github.com/rol-tools/lab-vpn.git
	```

2. Start the server

	```
	[student@workstation ~]$ ./lab-vpn/start-server
	starting vpn server...
	
	enter credentials:
	user: johndoe
	pass: *****
	
	vpn server started...
	hosts: lab-vpn.rol-tools.com
	ports: 2001/udp 888/tcp
	
	use Ctrl+C to stop...
	```

3. Connect to vpn from remote machine

## Contributing
Anyone is welcome to contribute. 

- Fork the repo.
- Create a new branch `git checkout -b new-feature`
- Commit your changes `git commit -am 'some contributions'`
- Push to your branch `git push -u origin new-feature`
- Submit a pull request.

## Supporting
> Support the community by supporting the growth of this project and many more projects to come.

[![buymeacoffee](https://res.cloudinary.com/smf19api4cloud/image/upload/c_thumb,w_200,g_face/v1661658836/misc/buymeacoffe_chnonk.png)](https://buymeacoffee.com/mfall) [![patreonimage](https://res.cloudinary.com/smf19api4cloud/image/upload/c_thumb,w_200,g_face/v1661658144/misc/become_a_patron_button3x_ygfryp.png)](https://patreon.com/mfall) 


## License
MIT
