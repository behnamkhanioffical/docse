Predeterminadamente, los tableros de proyecto en toda la organización y los que pertenecen a los usuarios son privados y solo los pueden ver las personas con permisos de lectura, escritura o administrativos en el tablero de proyecto. {% ifversion ghae %}Un tablero de proyecto interno{% else %}público{% endif %} será visible para {% ifversion ghae %}cualquier miembro de la empresa{% else %}cualquiera{% endif %} con la URL de dicho tablero de proyecto. Los tableros de proyecto a nivel de repositorio comparten la visibilidad de su repositorio respectivo. Esto significa que un repositorio privado tendrá un tablero privado y esta visibilidad no podrá cambiarse.