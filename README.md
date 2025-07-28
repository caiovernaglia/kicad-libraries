Caio Vernaglia's KiCad Libraries
================================

### Teoria
Quando um novo componente precisa ser adicionado à biblioteca, decidimos se vamos usar o símbolo padrão do KiCad ou se criamos um novo símbolo do começo. Daremos a preferência para o uso dos símbolos padrões. Os componentes serão criados usando a [KiCad Library Conventrion](https://klc.kicad.org) sempre que possível.

Adicionalmente, temos a necessidade de atribuir vários parâmetros relacionado à fabricação (ie: IPN, IMS Link...), para isso, existem vários componentes com o mesmo símbolo porém com parâmetros específicos.

Para nomeação, usamos a seguinte convenção:
* R_[resistance]\_[size]\_[wattage_optional]\_[tolerance]
* C_[capacitance]\_[size]\_[voltage]\_[tolerance]
* L_[inductance]\_[size]\_[max_current]
* LED_[color]\_[size]\_[wavelength_optional]

Contents
-------------------
* [/3dmodels](https://github.com/caiovernaglia/tree/main/3dmodels) -- 3D Models
* [/footprints](https://github.com/caiovernaglia/tree/main/footprints) -- PCB footprints
* [/symbols](https://github.com/caiovernaglia/tree/main/symbols) -- Schematic symbols

License
-------------------
Esse biblioteca é disponibilizada sobre a licença [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
**Você pode utilizar comercialmente esse biblioteca**