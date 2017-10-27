# Usage

roles:
  - { role: ar-docker-cleanup, mode: install, tags: ['docker', 'docker-cleanup'] }
  #lancement des containers Docker>
  - { role: ar-docker-cleanup, mode: clean, tags: ['docker', 'docker-cleanup'] }

Les modes : install dépose le script, clean le supprime, mais les deux nettoient les images inutiles.

# variables à surcharger

* path_depot_scripts : lieu de stockage du script de nettoyage

# Todo
