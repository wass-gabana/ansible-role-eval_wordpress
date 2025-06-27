# Rôle Ansible pour WordPress

Installe WordPress avec MariaDB sur Ubuntu et Rocky.

## Variables à modifier
Éditez `defaults/main.yml` pour :
- Changer mots de passe
- Modifier répertoire d'installation

## Après installation
1. Modifiez manuellement les clés de sécurité dans :
   `{{ wordpress_install_dir }}/wp-config.php`
2. Accédez à http://votre-serveur pour terminer l'installation