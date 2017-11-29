## {{ site.data.fhir.igName }}
{:.no_toc}

{% include publish-box.html %}

###  Extensions

Example:

```
  <Patient>
    <extension url="http://hl7.org/fhir/ig/vietnam/StructureDefinition/ethnicity">
      <valueCoding>
       <system value="http://hl7.org/fhir/ig/vietnam/CodeSystem/ethnicity"/>
       <code value="KINH"/>
      </valueCoding>
    </extension>
  </Patient>
```

{% include list-structuredefinitions.xhtml %}

