<title>  Configurer un scanner Trust 240 sous ubuntu </title>
<p> cd /tmp  </p>
<p> * Télécharger le fichier A2Dfw.usb dans le dossier /tmp  </p>
<p> wget http://www.meier-geinitz.de/sane/gt68xx-backend/firmware/A2Dfw.usb  </p>
<p> * Copier le fichier dans le dossier /usr/share/sane/gt68xx/  </p>
<p> sudo cp A2Dfw.usb /usr/share/sane/gt68xx/  </p>
<p> * Ajouter votre utilisateur au groupe saned  </p>
<p> sudo adduser nom_utilisateur saned  </p>
<p> il faut installer xsane et sane </p>
<p>  sudo sane-find-scanner -v </p>
<p>   scanimage -L </p>
<p>   scanimage -T </p>
<p>   sudo cp A2Dfw.usb /usr/share/sane/gt68xx/ </p>
<p> le repertoire gt68xx  n'est pas present </p>
<p>  mkdir /usr/share/sane/gt68xx/ </p>
<p>  sudo mkdir /usr/share/sane/gt68xx/ </p>
<p> sudo cp A2Dfw.usb /usr/share/sane/gt68xx/ </p>
<p>   sudo adduser esaid saned </p>
<p>   sudo sane-find-scanner -v </p>
<p>   scanimage -L </p>
<p>  scanimage -T </p>
<p>  xsane </p>
        
