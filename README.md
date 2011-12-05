Sonar PHP_CodeSniffer Rules Extension for Symfony2 Standards
============================================================

This extention adds the custom Symfony2 sniffs to the quality profile panel in Sonar.

It's based on the PHP_CodeSniffer [ruleset provided by opensky](https://github.com/opensky/Symfony2-coding-standard).

It's follow the [recommended sonar way to extends quality profile](http://docs.codehaus.org/display/SONAR/Extend+PHP+coding+rules#ExtendPHPcodingrules-Extendingphpcodesnifferrules).

Installation
------------

1. Simply copy the rules.xml at this path:

    $SONAR_HOME/extensions/rules/php_codesniffer_rules/rules.xml

2. Restart your sonar instance.

3. Check the configuration > quality profile panel, search for PHP_CodeSniffer inactive rules and expand all the rules. Every rules with a key starting by Symfony2 should be present.