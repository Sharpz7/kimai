[![CircleCI](https://circleci.com/gh/Sharpz7/kimai/tree/main.svg?style=svg)](https://circleci.com/gh/Sharpz7/kimai/tree/main)

# Vouch

A [Kimai Setup](https://github.com/kevinpapst/kimai2) setup designed to work with [SharpNet](https://github.com/SharpSet/sharpnet) and [SharpCD](https://github.com/SharpSet/sharpcd)

# Installation

- Make sure [SharpCD](https://github.com/SharpSet/sharpcd) has been installed.

- Create a sharpcd.yml file like the following:

- Ensure the enviromental variables have been set in an enviromental variable file:

```env
SQL_ROOT_PASS=NhmjAx5UQN%rmR
ADMIN_PASS=U%Z2RG@Pgn297d
```

- Run the following command to install vouch proxy:

```bash
sharpcd --remotefile https://raw.githubusercontent.com/Sharpz7/kimai/main/.sharpcd/install.yml
```

- For help with this step, see the [KimAI Docker Setup Repo](https://github.com/tobybatch/kimai2)

## Maintainers

- [Adam McArthur](https://adam.mcaq.me)