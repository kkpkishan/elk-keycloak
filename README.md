# elk-keycloak
<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/kkpkishan/elk-keycloak.git"> opendistro elk with keycloak</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
           <p>Install docker and docker-compose.</p>
           <h6>Create Details</h6>
           <ol>
            <li>change IP address in all the config files and set up proper keycloak and kibana details.
            <p>CMD: docker-compose -f keycloak.yml up -d</p></li>
            <li>Check keycloak working  
            <p>URL: http://IP:8080 </p>
             <p>  Username:admin </p>
             <p>  password:redhat </p></li>
            <li>keycloak first import oauth2.json in client</li>
            <li>Get securty token and change in kibana.yaml</li>
            <li>Run docker-compose.yaml file
            <p>CMD: docker-compose -f  up -d</p></li>
            <tr>
                      <td nowrap width="100%" valign="top">
        </td>
    </tr> 
 </table>


