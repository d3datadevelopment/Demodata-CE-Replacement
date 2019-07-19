# Demodata replacement if demodata aren't used (Community Edition)

This package removes the unused OXID demodata package from the shop.

## Hint

For installations of the Professional Edition and Enterprise Edition please use the packages under "d3/oxideshop-demodata-pe-replacement" (PE) or "d3/oxideshop-demodata-ee-replacement" (EE).

## Install

if the demodata aren't used and should be removed from the shop installation

* Run this composer statement in your shop. Adjust this instruction if your installation requires it.

    `composer require d3/oxideshop-demodata-ce-replacement --update-no-dev`
    
* Remove the installed demo data (e.g. pictures) from your installation in the source/out/pictures directory.

## Uninstall

If the demo data is to be reused

* Manually clean up the replacement module entry (d3/oxideshop-demodata-ce-replacement) from the vendor/composer/installed.json and composer.lock files.
* Run this composer statement in your shop. Adjust this instruction if your installation requires it.

    `composer remove d3/oxideshop-demodata-ce-replacement --update-no-dev`
