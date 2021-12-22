<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="images/logo.png" alt="Logo" width="700" height="400">
  <h2 align="center">Project 3</h2>
  <h3 align="center">HyperText Transfer Protocol Apache2</h3>
</div>



<!-- TABLE OF CONTENTS -->

  <summary>Table of Contents</summary>
  <ol>
     <li><a href="#Project-description">Project description</a></li>
    <li>
      <a href="#Part-I">Part I : DNS configuration</a>
         <ul>
              <li><a href="#Installation">Install the Apache2 server</a></li>
              <li><a href="#verification-the-configuration-files">Verify the configuration files and identify the role of each file:</a></li>
                  <ul> 
                      <li><a href="#role-of-each-file">apache2.conf, envvars, ports.conf, conf.d, sites-available, sites-enabled, mods-available and mods-enabled</a></li>
                  </ul>
              <li><a href="#Website-configuration">Website configuration.</a></li>       
           </ul>
        </li>
        <li><a href="#Part-II">Part II: HTTP and DNS</a>
            <ul>      
              <li><a href="#Configure-the-client">Configure the client</a></li>
              <li><a href="#Verify-the-configuration">Verify the configuration</a></li>
            </ul>
           </li> 
        <li><a href="#Part-III">Part III: Secure a repository</a>
             <ul>      
              <li><a href="#Access-filtering-at-users">Access filtering at users’ level</a></li>
                 <ul>      
                   <li><a href="#Modification-the-configuration">Modification the configuration</a></li>
                   <li><a href="#Create-accounts">Create accounts (Apache provides a tool to easily generate encrypted passwords)</a></li>
                 <ul>
                   <li><a href="#Create-a-password-for-the-admin-account">Create a password for the admin account</a></li>
                   <li><a href="#Verify-the-encrypting-of-the-username-and-the-password">Verify the encrypting of the username and the password</a></li>
                     </ul>
                 </ul>
              <li><a href="#Test-the-access-to-the-website">Test the access to the website, what do you notice?</a></li>
              <li><a href="#Check-if-the-password-is-encrypted">Check if the password is encrypted at the level of transfer from the client to the server</a></li>
              <li><a href="#What-is-the-solution">What is the solution?</a></li>
            </ul>
        </li>
        <li><a href="#Part-IV">Part IV: Configuration with .htaccess</a>
          <ul>      
             <li><a href="#Configure-Apache-with__htaccess">Configure Apache with .htaccess.</a></li>
               <ul>      
                <li><a href="#Authorize-the-modification">Authorize the modification</a></li>
                <li><a href="#Create-a-file-named-htaccess">Create a file named “.htaccess” in/var/www/mywebsite2/.</a></li>
                <li><a href="#Configure-the-htaccess">Configure the .htaccess.</a></li>
                <li><a href="#Create-the-digest_users-file">Create the digest-users file.</a></li>
              </ul>
             <li><a href="#Check-if-the-password-is-encrypted">Check if the password is encrypted</a></li>
          </ul>
        </li> 
        <li><a href="#Part-V">Part V: Personal Directories</a>
            <ul>      
              <li><a href="#Create-a-user">Create a user</a></li>
              <li><a href="#Each-user-must-have-a--public_html--folder-in-their-home-directory">Each user must have a “public_html” folder in their home directory</a></li>
            </ul>
         </li> 
   </ol>



# Project description:

>  Apache is an open-source web server that powers a large number of websites
> around the world. Its official name is Apache HTTP Server and it is maintained
> and developed by the Apache Software Foundation.
> 
>  Apache allows website owners to provide content on the web, hence the name
> “web server”. It is one of the oldest and most reliable web servers with a first
> version released over 25 years ago, in 1995.
> 
>  When a user wants to visit a website, they type a domain name (or IP address)
> in the browser’s bar. Then the web server delivers the requested files by acting as
> a virtual delivery agent.

# Part-I
## Installation
## verification-the-configuration-files
# role-of-each-file
## Website-configuration

<p align="right">(<a href="#top">back to top</a>)</p>

# Part-II
## Configure-the-client
## Verify-the-configuration

<p align="right">(<a href="#top">back to top</a>)</p>

# Part-III

# Access-filtering-at-users
# Modification-the-configuration
# Create-accounts
# Create-a-password-for-the-admin-account
# Verify-the-encrypting-of-the-username-and-the-password
# Test-the-access-to-the-website
# Check-if-the-password-is-encrypted
# What-is-the-solution




<p align="right">(<a href="#top">back to top</a>)</p>

# Part-IV

> The .htaccess files are Apache configuration files, allowing to define rules in
> a directory and in all its subdirectories (which do not have such a file inside). They
> can be used to protect a directory with a password, to change the name or
> extension of the index page, or to prohibit access to the directory.
> 
> The .htaccess file is placed in the directory in which it must act. It thus acts
> on the permissions of the directory that contains it and of all its sub-directories.
> Another .htaccess file can be placed in a subdirectory of a directory already
> controlled by an .htaccess file. The .htaccess file in the parent directory remains
> in “activity” until the functionality is rewritten.

# Configure-Apache-with__htaccess
# Authorize-the-modification
# Create-a-file-named-htaccess
# Configure-the-htaccess
# Create-the-digest_users-file
# Check-if-the-password-is-encrypted

<p align="right">(<a href="#top">back to top</a>)</p>

# Part-V
  
# Create-a-user
# Each-user-must-have-a--public_html--folder-in-their-home-directory  
<p align="center">
     <img src="images/part3.png">
   </p>

<p align="right">(<a href="#top">back to top</a>)</p>

Out Team - [AIT EL KADI Ilyas](https://github.com/IlyasKadi) - [AZIZ Oussama](https://github.com/ATAMAN0)

Project Link: [https://github.com/IlyasKadi/Domain-Name-System-Protocol](https://github.com/IlyasKadi/Domain-Name-System-Protocol)

<p align="right">(<a href="#top">back to top</a>)</p>
