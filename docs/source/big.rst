Tutorial
===============

This is a step by step guide to how to use the tool xxxxxxxxx.

.. code-block:: python

    import molecool

    benzene_symbols, benzene_coords = molecool.open_xyz('benzene.xyz')
    benzene_bonds = molecool.build_bond_list(benzene_coords)
    molecool.draw_molecule(benzene_coords, benzene_symbols, draw_bonds=benzene_bonds)

