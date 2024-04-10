Feature: BellyFeature

  Scenario: eaten many cukes and wait 2 hours and growl
    Given I have eaten 11 cukes
    When I wait 2 hour
    Then my belly should growl

  Scenario: eaten 11 cukes and wait 1 hour and not growl
    Given I have eaten 11 cukes
    When I wait 1 hour
    Then my belly should not growl

  Scenario: eaten 9 cukes and wait 2 hours and not growl
    Given I have eaten 9 cukes
    When I wait 2 hour
    Then my belly should not growl

  Scenario: eaten 9 cukes and wait 1 hour and not growl
    Given I have eaten 9 cukes
    When I wait 1 hour
    Then my belly should not growl




***************************************************************

Característica: BellyFeature

  Escenario: comido muchos cukes y esperar 2 horas y gruñir
    Dado que he comido 11 pepinos
    Cuando espero 2 horas
    Entonces mi vientre debe gruñir

  Escenario: comí 11 pepinos y esperé 1 hora y no gruñí
    Dado que he comido 11 pepinos
    Cuando espero 1 hora
    Entonces mi barriga no debería gruñir

  Escenario: comí 9 pepinos y esperé 2 horas y no gruñí
    Dado que he comido 9 pepinos
    Cuando espero 2 horas
    Entonces mi barriga no debe gruñir

Traducción realizada con la versión gratuita del traductor www.DeepL.com/Translator


*************************************************************************
import org.junit.jupiter.params.ParameterizedTest;
import org.junit.jupiter.params.provider.CsvSource;
import static org.assertj.core.api.Assertions.assertThat;
import org.junit.jupiter.api.BeforeEach;
import org.junit.jupiter.api.Test;
import org.junit.jupiter.params.ParameterizedTest;
import org.junit.jupiter.params.provider.CsvSource;
import static org.assertj.core.api.Assertions.assertThat;
package org.example;
import org.junit.jupiter.api.Test; //reconoce como una linea de prueba
import static org.assertj.core.api.Assertions.assertThat; //hace una importacion estatica de la clase assertj


import org.junit.jupiter.params.ParameterizedTest;
import org.junit.jupiter.params.provider.ValueSource;
import static org.assertj.core.api.Assertions.assertThat;
