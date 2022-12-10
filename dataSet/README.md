# Dota 2 Grid Editor

# Installation

If you want easy installation install Command Line Interface, if you want more control install manually.

## Command Line Interface
[Dota 2 Grid Editor CLI](https://pypi.org/project/dota2-grid-editor-cli/)


## Using Manually
1. Download as a zip file
2. Unzip
3. Use manual_execute.py to make grids, you can edit manual_execute.py to make changes to your grid.

```python

    role_grid('name_of_grid',list_of_heroes)
    create_hero_grid('name_of_grid', column_to_sort_by)
    
```

Execute.py editing documentation.

    Main Class For Making Grids

    ...

    Methods
    -------
    create_hero_grid(grid_name,column_to_sort_by,which_hero_list,heroes_per_line)
        Parameters
        ----------
        grid_name : str
            Name of the grid.
        sort_by : str
            column to sort by, for example ('winrate','personal_match_played').
        heroes_list : str
            'all' for of all heroes, 'played' for using heroes you've at least played for 2 matches.
        
        
        
    role_grid(grid_name,column_to_sort_by,which_hero_list)
        Parameters
        ----------
        grid_name : str
            Name of the grid.
        sort_by : str
            column to sort by, for example ('winrate','personal_match_played').
        heroes_list : str
            'all' for of all heroes, 'played' for using heroes you've at least played for 2 matches.