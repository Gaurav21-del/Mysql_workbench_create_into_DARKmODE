# Mysql_workbench_create_into_DARKmODE
Mysql_workbench_create_into_DARKmODE
# FORM LINE 11 TO 102 COPY AND PASTE INTO MYSQL PROPERTIES - FILE LOCATION DATA CODE EDITOR .XML FILE (PASTE) HERE.
<!-- This is the base language setting. It's usually not directly used, but provides values shared by
         more specialized MySQL versions. -->
    
    <!-- Lexer properties -->
    <property name="fold" value="1" />
    <property name="fold.compact" value="0" />
    <property name="fold.comment" value="1" />

    <!-- Editor settings -->
    <setting name="usetabs" value="1" />
    <setting name="tabwidth" value="4" />
    <setting name="indentation" value="4" />

    <!-- Keep in mind to use the same list names as defined in the lexers (e.g. LexMySQL.cpp). -->
    <keywords name="Major Keywords">
      <!-- Keywords that can start a statement. No longer used. -->
    </keywords>

    <keywords name="Keywords">
    </keywords>

    <keywords name="Procedure keywords">
      begin end comment
    </keywords>

    <keywords name="User Keywords 1">
      delimiter
    </keywords>

    <!-- These two lists are not used for syntax highlighting but assemble keywords from the other lists that serve a special purpose. -->
    <keywords name="User Keywords 2"> <!-- Keywords that are allowed at the start of an expression. -->
      binary case cast convert exists interval match not row
    </keywords>

    <keywords name="User Keywords 3"> <!-- Like user 2 but those that can appear between two expressions. -->
      all and any as between escape false in is like or regexp sounds true unknown xor
    </keywords>
    
    <style id="0" fore-color-light="#abb2bf" fore-color-dark="#abb2bf" back-color-light="#232729" /> <!-- SCE_MYSQL_DEFAULT -->

    <style id="1" fore-color-light="#5c6370" fore-color-dark="#5c6370" /> <!-- SCE_MYSQL_COMMENT -->
    <style id="2" fore-color-light="#5c6370" fore-color-dark="#5c6370" /> <!-- SCE_MYSQL_COMMENTLINE -->
    <style id="21" back-color-light="#F0F0F0" back-color-dark="#232729" /> <!-- SCE_MYSQL_HIDDENCOMMAND -->

    <style id="3" fore-color-light="#e06c75" fore-color-dark="#e06c75" /> <!-- SCE_MYSQL_VARIABLE -->
    <style id="4" fore-color-light="#e06c75" fore-color-dark="#e06c75" /> <!-- SCE_MYSQL_SYSTEMVARIABLE -->
    <style id="5" fore-color-light="#e06c75" fore-color-dark="#e06c75" /> <!-- SCE_MYSQL_KNOWNSYSTEMVARIABLE -->

    <style id="6" fore-color-light="#d19a66" fore-color-dark="#d19a66" /> <!-- SCE_MYSQL_NUMBER -->
    <style id="12" fore-color-light="#98c379" fore-color-dark="#98c379" /> <!-- SCE_MYSQL_SQSTRING -->
    <style id="13" fore-color-light="#98c379" fore-color-dark="#98c379" /> <!-- SCE_MYSQL_DQSTRING -->

    <style id="7" bold="Yes" fore-color-light="#56b6c2" /> <!-- SCE_MYSQL_MAJORKEYWORD -->
    <style id="8" bold="Yes" fore-color-light="#61afef" /> <!-- SCE_MYSQL_KEYWORD -->
    <style id="15" fore-color-light="#c678dd" fore-color-dark="#c678dd" /> <!-- SCE_MYSQL_FUNCTION -->
    <style id="10" fore-color-light="#c678dd" fore-color-dark="#c678dd" /> <!-- SCE_MYSQL_PROCEDUREKEYWORD -->
    <style id="14" bold="Yes" /> <!-- SCE_MYSQL_OPERATOR -->

    <style id="16" fore-color-light="#eaeaea" fore-color-dark="#eaeaea" /> <!-- SCE_MYSQL_IDENTIFIER -->
    <style id="17" fore-color-light="#eaeaea" fore-color-dark="#eaeaea" /> <!-- SCE_MYSQL_QUOTEDIDENTIFIER -->

    <style id="22" fore-color-light="#ABB2BF" back-color-light="#232729" fore-color-dark="#ABB2BF" back-color-dark="#232729" bold="Yes" /> <!-- SCE_MYSQL_PLACEHOLDER -->

    <style id="18" fore-color-light="#98c379" fore-color-dark="#98c379" bold="yes"/> <!-- SCE_MYSQL_USER1 -->

    <style id="32" fore-color-light="#ABB2BF" back-color-light="#232729" fore-color-dark="#ABB2BF" back-color-dark="#232729" /> <!-- OVERALL BACKGROUND -->
    <style id="33" fore-color-light="#ABB2BF" back-color-light="#21252b" fore-color-dark="#ABB2BF" back-color-dark="#21252b" /> <!-- LINE NUMBER BACKGROUND -->

    <!-- All styles again in their variant in a hidden command (with a 0x40 offset). -->
    <style id="65" fore-color-light="#5c6370" back-color-light="#232729" fore-color-dark="#5c6370" back-color-dark="#232729" /> <!-- SCE_MYSQL_COMMENT -->
    <style id="66" fore-color-light="#5c6370" back-color-light="#232729" fore-color-dark="#5c6370" back-color-dark="#232729" /> <!-- SCE_MYSQL_COMMENTLINE -->

    <style id="67" fore-color-light="#e06c75" back-color-light="#232729" fore-color-dark="#e06c75" back-color-dark="#232729" /> <!-- SCE_MYSQL_VARIABLE -->
    <style id="68" fore-color-light="#e06c75" back-color-light="#232729" fore-color-dark="#e06c75" back-color-dark="#232729" /> <!-- SCE_MYSQL_SYSTEMVARIABLE -->
    <style id="69" fore-color-light="#e06c75" back-color-light="#232729" fore-color-dark="#e06c75" back-color-dark="#232729" /> <!-- SCE_MYSQL_KNOWNSYSTEMVARIABLE -->

    <style id="70" fore-color-light="#d19a66" back-color-light="#232729" fore-color-dark="#d19a66" back-color-dark="#232729" /> <!-- SCE_MYSQL_NUMBER -->
    <style id="76" fore-color-light="#98c379" back-color-light="#232729" fore-color-dark="#98c379" back-color-dark="#232729" /> <!-- SCE_MYSQL_SQSTRING -->
    <style id="77" fore-color-light="#98c379" back-color-light="#232729" fore-color-dark="#98c379" back-color-dark="#232729" /> <!-- SCE_MYSQL_DQSTRING -->

    <style id="71" back-color-light="#232729" back-color-dark="#232729" bold="Yes" /> <!-- SCE_MYSQL_MAJORKEYWORD -->
    <style id="72" back-color-light="#232729" back-color-dark="#232729" bold="Yes"/> <!-- SCE_MYSQL_KEYWORD -->
    <style id="79" fore-color-light="#c678dd" back-color-light="#232729" fore-color-dark="#c678dd" back-color-dark="#232729" /> <!-- SCE_MYSQL_FUNCTION -->
    <style id="74" fore-color-light="#c678dd" back-color-light="#232729" fore-color-dark="#c678dd" back-color-dark="#232729" /> <!-- SCE_MYSQL_PROCEDUREKEYWORD -->
    <style id="78" back-color-light="#232729" back-color-dark="#232729" bold="Yes" /> <!-- SCE_MYSQL_OPERATOR -->

    <style id="80" fore-color-light="#eaeaea" back-color-light="#232729" fore-color-dark="#eaeaea" back-color-dark="#232729" /> <!-- SCE_MYSQL_IDENTIFIER -->
    <style id="81" fore-color-light="#eaeaea" back-color-light="#232729" fore-color-dark="#eaeaea" back-color-dark="#232729" /> <!-- SCE_MYSQL_QUOTEDIDENTIFIER -->

    <style id="86" fore-color-light="#ABB2BF" back-color-light="#232729" fore-color-dark="#ABB2BF" back-color-dark="#232729" bold="Yes" /> <!-- SCE_MYSQL_PLACEHOLDER -->

    <style id="82" fore-color-light="#98c379" back-color-light="#232729" fore-color-dark="#98c379" back-color-dark="#232729" bold="yes"/> <!-- SCE_MYSQL_USER1 -->

