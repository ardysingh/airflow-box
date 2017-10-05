# airflow-box

Vagrant box definition for an Ubuntu image. Install airflow and it's dependencies.
Also maps the guest OS port 8080 to host port 8080.

"vagrant up" should do it all.

Once box is booted up, log into the box using (on a mac)

	vagrant ssh

From the shell, use the following to start the Airflow webserver

	airflow webserver -p 8080
