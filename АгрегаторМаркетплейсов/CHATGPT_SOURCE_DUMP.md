# Полный дамп исходников и метаданных

Дата снимка: 2026-04-28

Ниже приведены все текстовые файлы проекта в текущем состоянии.

Количество файлов: 34

## FILE: .project
```text
<?xml version="1.0" encoding="UTF-8"?>
<projectDescription>
	<name>АгрегаторМаркетплейсов</name>
	<comment></comment>
	<projects>
	</projects>
	<buildSpec>
		<buildCommand>
			<name>org.eclipse.xtext.ui.shared.xtextBuilder</name>
			<arguments>
			</arguments>
		</buildCommand>
	</buildSpec>
	<natures>
		<nature>org.eclipse.xtext.ui.shared.xtextNature</nature>
		<nature>com._1c.g5.v8.dt.core.V8ConfigurationNature</nature>
	</natures>
</projectDescription>
```

## FILE: DT-INF/PROJECT.PMF
```text
Manifest-Version: 1.0
Runtime-Version: 8.5.1
```

## FILE: src/AccumulationRegisters/ПродажиМаркетплейсов/ПродажиМаркетплейсов.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:AccumulationRegister xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="690cc038-8444-415b-8673-92ace21e1bf4">
  <producedTypes>
    <selectionType typeId="ea68636a-1f9a-4b72-84bc-d0469d34532d" valueTypeId="d3ac1cba-9b8e-4d64-94f8-4193a5959b43"/>
    <listType typeId="55212dda-5f4e-44b3-8f74-54722527d789" valueTypeId="4d49ce5d-d251-4769-8e01-e0b885b43375"/>
    <managerType typeId="64131b37-0488-44c5-94f8-f363dd755db4" valueTypeId="73d9ba45-22a3-449e-a121-d56e569f3c59"/>
    <recordSetType typeId="a4e42251-89a4-4daf-b960-72457d8e7597" valueTypeId="453b05dc-6c3f-4663-ad20-1a993166b2cc"/>
    <recordKeyType typeId="129ecbcd-7f19-445a-8d25-75b10a9d5b7b" valueTypeId="fd6e5bf1-b075-4e34-9fa5-2f7d2aef884f"/>
    <recordType typeId="d64c8b3e-8666-46a4-b5d0-13566675799f" valueTypeId="3831678c-5c31-4efe-a0e1-2927a18f1abd"/>
  </producedTypes>
  <name>ПродажиМаркетплейсов</name>
  <synonym>
    <key>ru</key>
    <value>Продажи маркетплейсов</value>
  </synonym>
  <useStandardCommands>true</useStandardCommands>
  <dataLockControlMode>Managed</dataLockControlMode>
  <enableTotalsSplitting>true</enableTotalsSplitting>
  <resources uuid="d0fa40ec-7cb4-44c3-9075-eb10dcb8f222">
    <name>Количество</name>
    <synonym>
      <key>ru</key>
      <value>Количество</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>15</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
  </resources>
  <resources uuid="7b15b062-d122-4a76-b6db-ff7d4e2e18c8">
    <name>СуммаПродажи</name>
    <synonym>
      <key>ru</key>
      <value>Сумма продажи</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>15</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
  </resources>
  <resources uuid="6c3f38e4-9ad6-4aa7-83ec-a9dc06886c7e">
    <name>СуммаКомиссии</name>
    <synonym>
      <key>ru</key>
      <value>Сумма комиссии</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>15</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
  </resources>
  <resources uuid="fc171132-5ed4-4a16-bf03-b24fe91ab986">
    <name>Себестоимость</name>
    <synonym>
      <key>ru</key>
      <value>Себестоимость</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>15</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
  </resources>
  <resources uuid="cb45998f-ef06-43c0-a2ee-62e959d0f85d">
    <name>ЧистаяПрибыль</name>
    <synonym>
      <key>ru</key>
      <value>Чистая прибыль</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>15</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
  </resources>
  <dimensions uuid="50020c0f-ac6e-485a-993d-e9034e978a7d">
    <name>Товар</name>
    <synonym>
      <key>ru</key>
      <value>Товар</value>
    </synonym>
    <type>
      <types>CatalogRef.Товары</types>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <useInTotals>true</useInTotals>
  </dimensions>
  <dimensions uuid="039f1dff-ed88-4afe-91ee-f0ac3192a521">
    <name>Маркетплейс</name>
    <synonym>
      <key>ru</key>
      <value>Маркетплейс</value>
    </synonym>
    <type>
      <types>CatalogRef.Маркетплейсы</types>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <useInTotals>true</useInTotals>
  </dimensions>
</mdclass:AccumulationRegister>
```

## FILE: src/Catalogs/Контрагенты/Forms/ФормаСписка/Attributes/Список/ExtInfo/ListSettings.dcss
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Settings xmlns="http://v8.1c.ru/8.1/data-composition-system/settings" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xs="http://www.w3.org/2001/XMLSchema" xmlns:v8="http://v8.1c.ru/8.1/data/core" xmlns:v8ui="http://v8.1c.ru/8.1/data/ui" xmlns:pal="http://v8.1c.ru/8.1/data/ui/colors/palette" xmlns:style="http://v8.1c.ru/8.1/data/ui/style" xmlns:sys="http://v8.1c.ru/8.1/data/ui/fonts/system" xmlns:web="http://v8.1c.ru/8.1/data/ui/colors/web" xmlns:win="http://v8.1c.ru/8.1/data/ui/colors/windows" xmlns:dcscor="http://v8.1c.ru/8.1/data-composition-system/core">
	<filter>
		<viewMode>Normal</viewMode>
		<userSettingID>dfcece9d-5077-440b-b6b3-45a5cb4538eb</userSettingID>
	</filter>
	<order>
		<viewMode>Normal</viewMode>
		<userSettingID>88619765-ccb3-46c6-ac52-38e9c992ebd4</userSettingID>
	</order>
	<conditionalAppearance>
		<viewMode>Normal</viewMode>
		<userSettingID>b75fecce-942b-4aed-abc9-e6a02e460fb3</userSettingID>
	</conditionalAppearance>
	<itemsViewMode>Normal</itemsViewMode>
	<itemsUserSettingID>911b6018-f537-43e8-a417-da56b22f9aec</itemsUserSettingID>
</Settings>
```

## FILE: src/Catalogs/Контрагенты/Forms/ФормаСписка/Form.form
```xml
<?xml version="1.0" encoding="UTF-8"?>
<form:Form xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:form="http://g5.1c.ru/v8/dt/form">
  <items xsi:type="form:FormGroup">
    <name>СписокКомпоновщикНастроекПользовательскиеНастройки</name>
    <id>1</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <title>
      <key>ru</key>
      <value>Группа пользовательских настроек</value>
    </title>
    <verticalStretch>false</verticalStretch>
    <extendedTooltip>
      <name>СписокКомпоновщикНастроекПользовательскиеНастройкиРасширеннаяПодсказка</name>
      <id>2</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <type>UsualGroup</type>
    <extInfo xsi:type="form:UsualGroupExtInfo">
      <group>Vertical</group>
      <behavior>Auto</behavior>
      <representation>WeakSeparation</representation>
      <showLeftMargin>true</showLeftMargin>
      <united>true</united>
      <throughAlign>Auto</throughAlign>
      <currentRowUse>Auto</currentRowUse>
    </extInfo>
  </items>
  <items xsi:type="form:Table">
    <name>Список</name>
    <id>3</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Список</segments>
    </dataPath>
    <defaultItem>true</defaultItem>
    <titleLocation>None</titleLocation>
    <items xsi:type="form:FormField">
      <name>Код</name>
      <id>16</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Code</segments>
      </dataPath>
      <defaultItem>true</defaultItem>
      <extendedTooltip>
        <name>КодРасширеннаяПодсказка</name>
        <id>18</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>КодКонтекстноеМеню</name>
        <id>17</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>Наименование</name>
      <id>19</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Description</segments>
      </dataPath>
      <extendedTooltip>
        <name>НаименованиеРасширеннаяПодсказка</name>
        <id>21</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>НаименованиеКонтекстноеМеню</name>
        <id>20</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ИНН</name>
      <id>22</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.ИНН</segments>
      </dataPath>
      <extendedTooltip>
        <name>ИННРасширеннаяПодсказка</name>
        <id>24</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ИННКонтекстноеМеню</name>
        <id>23</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <autoCommandBar>
      <name>СписокКоманднаяПанель</name>
      <id>5</id>
      <horizontalAlign>Left</horizontalAlign>
      <autoFill>true</autoFill>
    </autoCommandBar>
    <searchStringAddition>
      <name>СписокСтрокаПоиска</name>
      <id>7</id>
      <extendedTooltip>
        <name>СписокСтрокаПоискаРасширеннаяПодсказка</name>
        <id>9</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСтрокаПоискаКонтекстноеМеню</name>
        <id>8</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <source>Список</source>
      <extInfo xsi:type="form:SearchStringAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchStringAddition>
    <viewStatusAddition>
      <name>СписокСостояниеПросмотра</name>
      <id>10</id>
      <extendedTooltip>
        <name>СписокСостояниеПросмотраРасширеннаяПодсказка</name>
        <id>12</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСостояниеПросмотраКонтекстноеМеню</name>
        <id>11</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>ViewStatusAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:ViewStatusAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </viewStatusAddition>
    <searchControlAddition>
      <name>СписокУправлениеПоиском</name>
      <id>13</id>
      <extendedTooltip>
        <name>СписокУправлениеПоискомРасширеннаяПодсказка</name>
        <id>15</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокУправлениеПоискомКонтекстноеМеню</name>
        <id>14</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>SearchControlAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:SearchControlAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchControlAddition>
    <extendedTooltip>
      <name>СписокРасширеннаяПодсказка</name>
      <id>6</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>СписокКонтекстноеМеню</name>
      <id>4</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <changeRowSet>true</changeRowSet>
    <changeRowOrder>true</changeRowOrder>
    <autoMaxWidth>true</autoMaxWidth>
    <autoMaxHeight>true</autoMaxHeight>
    <autoMaxRowsCount>true</autoMaxRowsCount>
    <selectionMode>MultiRow</selectionMode>
    <rowSelectionMode>Auto</rowSelectionMode>
    <header>true</header>
    <headerHeight>1</headerHeight>
    <footerHeight>1</footerHeight>
    <horizontalScrollBar>AutoUse</horizontalScrollBar>
    <verticalScrollBar>AutoUse</verticalScrollBar>
    <horizontalLines>true</horizontalLines>
    <verticalLines>true</verticalLines>
    <searchOnInput>Auto</searchOnInput>
    <initialListView>Auto</initialListView>
    <initialTreeView>ExpandTopLevel</initialTreeView>
    <initialRowActivation>Activate</initialRowActivation>
    <horizontalStretch>true</horizontalStretch>
    <verticalStretch>true</verticalStretch>
    <enableStartDrag>true</enableStartDrag>
    <fileDragMode>AsFileRef</fileDragMode>
    <rowPictureDataPath xsi:type="form:DataPath">
      <segments>Список.DefaultPicture</segments>
    </rowPictureDataPath>
    <autoMaxCardHeight>true</autoMaxCardHeight>
    <extInfo xsi:type="form:DynamicListTableExtInfo">
      <autoRefreshPeriod>60</autoRefreshPeriod>
      <period>
        <startDate>0001-01-01T00:00:00</startDate>
        <endDate>0001-01-01T00:00:00</endDate>
      </period>
      <topLevelParent xsi:type="core:UndefinedValue"/>
      <showRoot>true</showRoot>
      <allowGettingCurrentRowURL>true</allowGettingCurrentRowURL>
      <userSettingsGroup>СписокКомпоновщикНастроекПользовательскиеНастройки</userSettingsGroup>
    </extInfo>
    <showCommandBarNeedDereferenced>true</showCommandBarNeedDereferenced>
  </items>
  <autoCommandBar>
    <name>ФормаКоманднаяПанель</name>
    <id>-1</id>
    <horizontalAlign>Left</horizontalAlign>
    <autoFill>true</autoFill>
  </autoCommandBar>
  <saveWindowSettings>true</saveWindowSettings>
  <autoTitle>true</autoTitle>
  <autoUrl>true</autoUrl>
  <group>Auto</group>
  <autoFillCheck>true</autoFillCheck>
  <allowFormCustomize>true</allowFormCustomize>
  <enabled>true</enabled>
  <showTitle>auto</showTitle>
  <showCloseButton>true</showCloseButton>
  <attributes>
    <name>Список</name>
    <id>1</id>
    <valueType>
      <types>DynamicList</types>
    </valueType>
    <view>
      <common>true</common>
    </view>
    <edit>
      <common>true</common>
    </edit>
    <main>true</main>
    <extInfo xsi:type="form:DynamicListExtInfo">
      <mainTable>Catalog.Контрагенты</mainTable>
      <dynamicDataRead>true</dynamicDataRead>
      <autoFillAvailableFields>true</autoFillAvailableFields>
      <autoSaveUserSettings>true</autoSaveUserSettings>
      <getInvisibleFieldPresentations>true</getInvisibleFieldPresentations>
    </extInfo>
  </attributes>
  <commandInterface>
    <navigationPanel/>
    <commandBar/>
  </commandInterface>
  <extInfo xsi:type="form:DynamicListFormExtInfo"/>
</form:Form>
```

## FILE: src/Catalogs/Контрагенты/Контрагенты.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Catalog xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="524d139e-ebd0-4b0f-ae6a-7ba884e5e0a1">
  <producedTypes>
    <objectType typeId="ac949220-e5c5-49ef-8713-9352d12be286" valueTypeId="6b52d756-63bc-4388-b998-b310e34de036"/>
    <refType typeId="0327468c-f716-426a-aaf8-29b15b192870" valueTypeId="569a98bf-7e5f-4f05-b8bc-097ccc3a5060"/>
    <selectionType typeId="82219485-109b-4dc7-b88b-d5fde8c216a2" valueTypeId="31bb26ba-ba7a-4a40-b68a-a72183ac7804"/>
    <listType typeId="cc1bbde1-b189-4a42-844b-9b5910671665" valueTypeId="0d1122dd-eb26-4ebd-bab3-d4b02b5a372d"/>
    <managerType typeId="f8926ea7-3c06-40bc-8158-ccf4bebcf8fd" valueTypeId="49c00652-76a7-4c13-9cd5-2e2e1e1366db"/>
  </producedTypes>
  <name>Контрагенты</name>
  <synonym>
    <key>ru</key>
    <value>Контрагенты</value>
  </synonym>
  <useStandardCommands>true</useStandardCommands>
  <inputByString>Catalog.Контрагенты.StandardAttribute.Code</inputByString>
  <inputByString>Catalog.Контрагенты.StandardAttribute.Description</inputByString>
  <fullTextSearchOnInputByString>DontUse</fullTextSearchOnInputByString>
  <createOnInput>Use</createOnInput>
  <dataLockControlMode>Managed</dataLockControlMode>
  <fullTextSearch>Use</fullTextSearch>
  <levelCount>2</levelCount>
  <foldersOnTop>true</foldersOnTop>
  <codeLength>9</codeLength>
  <descriptionLength>25</descriptionLength>
  <codeType>String</codeType>
  <codeAllowedLength>Variable</codeAllowedLength>
  <checkUnique>true</checkUnique>
  <autonumbering>true</autonumbering>
  <defaultPresentation>AsDescription</defaultPresentation>
  <editType>InDialog</editType>
  <choiceMode>BothWays</choiceMode>
  <defaultListForm>Catalog.Контрагенты.Form.ФормаСписка</defaultListForm>
  <attributes uuid="14825a33-d357-44f3-9a1f-4839d54d660a">
    <name>ИНН</name>
    <synonym>
      <key>ru</key>
      <value>ИНН</value>
    </synonym>
    <type>
      <types>String</types>
      <stringQualifiers>
        <length>12</length>
        <fixed>true</fixed>
      </stringQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fillValue xsi:type="core:StringValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <dataHistory>Use</dataHistory>
  </attributes>
  <forms uuid="1c80d32f-3f62-42c1-ba74-eb9e7ea55f89">
    <name>ФормаСписка</name>
    <synonym>
      <key>ru</key>
      <value>Форма списка</value>
    </synonym>
    <usePurposes>PersonalComputer</usePurposes>
    <usePurposes>MobileDevice</usePurposes>
  </forms>
</mdclass:Catalog>
```

## FILE: src/Catalogs/Маркетплейсы/Forms/ФормаСписка/Attributes/Список/ExtInfo/ListSettings.dcss
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Settings xmlns="http://v8.1c.ru/8.1/data-composition-system/settings" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xs="http://www.w3.org/2001/XMLSchema" xmlns:v8="http://v8.1c.ru/8.1/data/core" xmlns:v8ui="http://v8.1c.ru/8.1/data/ui" xmlns:pal="http://v8.1c.ru/8.1/data/ui/colors/palette" xmlns:style="http://v8.1c.ru/8.1/data/ui/style" xmlns:sys="http://v8.1c.ru/8.1/data/ui/fonts/system" xmlns:web="http://v8.1c.ru/8.1/data/ui/colors/web" xmlns:win="http://v8.1c.ru/8.1/data/ui/colors/windows" xmlns:dcscor="http://v8.1c.ru/8.1/data-composition-system/core">
	<filter>
		<viewMode>Normal</viewMode>
		<userSettingID>dfcece9d-5077-440b-b6b3-45a5cb4538eb</userSettingID>
	</filter>
	<order>
		<viewMode>Normal</viewMode>
		<userSettingID>88619765-ccb3-46c6-ac52-38e9c992ebd4</userSettingID>
	</order>
	<conditionalAppearance>
		<viewMode>Normal</viewMode>
		<userSettingID>b75fecce-942b-4aed-abc9-e6a02e460fb3</userSettingID>
	</conditionalAppearance>
	<itemsViewMode>Normal</itemsViewMode>
	<itemsUserSettingID>911b6018-f537-43e8-a417-da56b22f9aec</itemsUserSettingID>
</Settings>
```

## FILE: src/Catalogs/Маркетплейсы/Forms/ФормаСписка/Form.form
```xml
<?xml version="1.0" encoding="UTF-8"?>
<form:Form xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:form="http://g5.1c.ru/v8/dt/form">
  <items xsi:type="form:FormGroup">
    <name>СписокКомпоновщикНастроекПользовательскиеНастройки</name>
    <id>1</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <title>
      <key>ru</key>
      <value>Группа пользовательских настроек</value>
    </title>
    <verticalStretch>false</verticalStretch>
    <extendedTooltip>
      <name>СписокКомпоновщикНастроекПользовательскиеНастройкиРасширеннаяПодсказка</name>
      <id>2</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <type>UsualGroup</type>
    <extInfo xsi:type="form:UsualGroupExtInfo">
      <group>Vertical</group>
      <behavior>Auto</behavior>
      <representation>WeakSeparation</representation>
      <showLeftMargin>true</showLeftMargin>
      <united>true</united>
      <throughAlign>Auto</throughAlign>
      <currentRowUse>Auto</currentRowUse>
    </extInfo>
  </items>
  <items xsi:type="form:Table">
    <name>Список</name>
    <id>3</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Список</segments>
    </dataPath>
    <defaultItem>true</defaultItem>
    <titleLocation>None</titleLocation>
    <items xsi:type="form:FormField">
      <name>Код</name>
      <id>16</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Code</segments>
      </dataPath>
      <defaultItem>true</defaultItem>
      <extendedTooltip>
        <name>КодРасширеннаяПодсказка</name>
        <id>18</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>КодКонтекстноеМеню</name>
        <id>17</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>Наименование</name>
      <id>19</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Description</segments>
      </dataPath>
      <extendedTooltip>
        <name>НаименованиеРасширеннаяПодсказка</name>
        <id>21</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>НаименованиеКонтекстноеМеню</name>
        <id>20</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>КомиссияПроцент</name>
      <id>22</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.КомиссияПроцент</segments>
      </dataPath>
      <extendedTooltip>
        <name>КомиссияПроцентРасширеннаяПодсказка</name>
        <id>24</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>КомиссияПроцентКонтекстноеМеню</name>
        <id>23</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <autoCommandBar>
      <name>СписокКоманднаяПанель</name>
      <id>5</id>
      <horizontalAlign>Left</horizontalAlign>
      <autoFill>true</autoFill>
    </autoCommandBar>
    <searchStringAddition>
      <name>СписокСтрокаПоиска</name>
      <id>7</id>
      <extendedTooltip>
        <name>СписокСтрокаПоискаРасширеннаяПодсказка</name>
        <id>9</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСтрокаПоискаКонтекстноеМеню</name>
        <id>8</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <source>Список</source>
      <extInfo xsi:type="form:SearchStringAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchStringAddition>
    <viewStatusAddition>
      <name>СписокСостояниеПросмотра</name>
      <id>10</id>
      <extendedTooltip>
        <name>СписокСостояниеПросмотраРасширеннаяПодсказка</name>
        <id>12</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСостояниеПросмотраКонтекстноеМеню</name>
        <id>11</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>ViewStatusAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:ViewStatusAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </viewStatusAddition>
    <searchControlAddition>
      <name>СписокУправлениеПоиском</name>
      <id>13</id>
      <extendedTooltip>
        <name>СписокУправлениеПоискомРасширеннаяПодсказка</name>
        <id>15</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокУправлениеПоискомКонтекстноеМеню</name>
        <id>14</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>SearchControlAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:SearchControlAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchControlAddition>
    <extendedTooltip>
      <name>СписокРасширеннаяПодсказка</name>
      <id>6</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>СписокКонтекстноеМеню</name>
      <id>4</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <changeRowSet>true</changeRowSet>
    <changeRowOrder>true</changeRowOrder>
    <autoMaxWidth>true</autoMaxWidth>
    <autoMaxHeight>true</autoMaxHeight>
    <autoMaxRowsCount>true</autoMaxRowsCount>
    <selectionMode>MultiRow</selectionMode>
    <rowSelectionMode>Auto</rowSelectionMode>
    <header>true</header>
    <headerHeight>1</headerHeight>
    <footerHeight>1</footerHeight>
    <horizontalScrollBar>AutoUse</horizontalScrollBar>
    <verticalScrollBar>AutoUse</verticalScrollBar>
    <horizontalLines>true</horizontalLines>
    <verticalLines>true</verticalLines>
    <searchOnInput>Auto</searchOnInput>
    <initialListView>Auto</initialListView>
    <initialTreeView>ExpandTopLevel</initialTreeView>
    <initialRowActivation>Activate</initialRowActivation>
    <horizontalStretch>true</horizontalStretch>
    <verticalStretch>true</verticalStretch>
    <enableStartDrag>true</enableStartDrag>
    <fileDragMode>AsFileRef</fileDragMode>
    <rowPictureDataPath xsi:type="form:DataPath">
      <segments>Список.DefaultPicture</segments>
    </rowPictureDataPath>
    <autoMaxCardHeight>true</autoMaxCardHeight>
    <extInfo xsi:type="form:DynamicListTableExtInfo">
      <autoRefreshPeriod>60</autoRefreshPeriod>
      <period>
        <startDate>0001-01-01T00:00:00</startDate>
        <endDate>0001-01-01T00:00:00</endDate>
      </period>
      <topLevelParent xsi:type="core:UndefinedValue"/>
      <showRoot>true</showRoot>
      <allowGettingCurrentRowURL>true</allowGettingCurrentRowURL>
      <userSettingsGroup>СписокКомпоновщикНастроекПользовательскиеНастройки</userSettingsGroup>
    </extInfo>
    <showCommandBarNeedDereferenced>true</showCommandBarNeedDereferenced>
  </items>
  <autoCommandBar>
    <name>ФормаКоманднаяПанель</name>
    <id>-1</id>
    <horizontalAlign>Left</horizontalAlign>
    <autoFill>true</autoFill>
  </autoCommandBar>
  <saveWindowSettings>true</saveWindowSettings>
  <autoTitle>true</autoTitle>
  <autoUrl>true</autoUrl>
  <group>Auto</group>
  <autoFillCheck>true</autoFillCheck>
  <allowFormCustomize>true</allowFormCustomize>
  <enabled>true</enabled>
  <showTitle>auto</showTitle>
  <showCloseButton>true</showCloseButton>
  <attributes>
    <name>Список</name>
    <id>1</id>
    <valueType>
      <types>DynamicList</types>
    </valueType>
    <view>
      <common>true</common>
    </view>
    <edit>
      <common>true</common>
    </edit>
    <main>true</main>
    <extInfo xsi:type="form:DynamicListExtInfo">
      <mainTable>Catalog.Маркетплейсы</mainTable>
      <dynamicDataRead>true</dynamicDataRead>
      <autoFillAvailableFields>true</autoFillAvailableFields>
      <autoSaveUserSettings>true</autoSaveUserSettings>
      <getInvisibleFieldPresentations>true</getInvisibleFieldPresentations>
    </extInfo>
  </attributes>
  <commandInterface>
    <navigationPanel/>
    <commandBar/>
  </commandInterface>
  <extInfo xsi:type="form:DynamicListFormExtInfo"/>
</form:Form>
```

## FILE: src/Catalogs/Маркетплейсы/Маркетплейсы.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Catalog xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="9f7202f0-2199-4b8a-ab31-553abdfc2b2b">
  <producedTypes>
    <objectType typeId="9b0192dd-5c3f-456f-8495-24c2697fd286" valueTypeId="edac1373-537f-4bc3-9213-914c3ba3720c"/>
    <refType typeId="b2491c5b-d582-482e-b5eb-c83258fce0bb" valueTypeId="90ea3142-71e4-4f4c-8ba3-a569d0fbd100"/>
    <selectionType typeId="5536f219-5399-4798-9cc4-2f2494edbcaa" valueTypeId="f4d0abcc-c4e5-46f8-acf7-4ac7177fa664"/>
    <listType typeId="b011c9fa-2b62-4925-a2c0-b49a2ee5a823" valueTypeId="3907b3c5-1559-497c-8d6a-e8d485e63921"/>
    <managerType typeId="472f583a-e6c7-45e6-9eb7-9bd861b8c719" valueTypeId="de230ee3-e018-481c-8913-f4609989d46d"/>
  </producedTypes>
  <name>Маркетплейсы</name>
  <synonym>
    <key>ru</key>
    <value>Маркетплейсы</value>
  </synonym>
  <useStandardCommands>true</useStandardCommands>
  <inputByString>Catalog.Маркетплейсы.StandardAttribute.Code</inputByString>
  <inputByString>Catalog.Маркетплейсы.StandardAttribute.Description</inputByString>
  <fullTextSearchOnInputByString>DontUse</fullTextSearchOnInputByString>
  <createOnInput>Use</createOnInput>
  <dataLockControlMode>Managed</dataLockControlMode>
  <fullTextSearch>Use</fullTextSearch>
  <levelCount>2</levelCount>
  <foldersOnTop>true</foldersOnTop>
  <codeLength>9</codeLength>
  <descriptionLength>25</descriptionLength>
  <codeType>String</codeType>
  <codeAllowedLength>Variable</codeAllowedLength>
  <checkUnique>true</checkUnique>
  <autonumbering>true</autonumbering>
  <defaultPresentation>AsDescription</defaultPresentation>
  <editType>InDialog</editType>
  <choiceMode>BothWays</choiceMode>
  <defaultListForm>Catalog.Маркетплейсы.Form.ФормаСписка</defaultListForm>
  <attributes uuid="6169ff54-9746-407b-9be7-244f5df7ea96">
    <name>КомиссияПроцент</name>
    <synonym>
      <key>ru</key>
      <value>Комиссия процент</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>10</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fillValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <dataHistory>Use</dataHistory>
  </attributes>
  <forms uuid="9fe248f6-8411-4f62-b74d-6449db953a19">
    <name>ФормаСписка</name>
    <synonym>
      <key>ru</key>
      <value>Форма списка</value>
    </synonym>
    <usePurposes>PersonalComputer</usePurposes>
    <usePurposes>MobileDevice</usePurposes>
  </forms>
</mdclass:Catalog>
```

## FILE: src/Catalogs/Товары/Forms/ФормаСписка/Attributes/Список/ExtInfo/ListSettings.dcss
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Settings xmlns="http://v8.1c.ru/8.1/data-composition-system/settings" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xs="http://www.w3.org/2001/XMLSchema" xmlns:v8="http://v8.1c.ru/8.1/data/core" xmlns:v8ui="http://v8.1c.ru/8.1/data/ui" xmlns:pal="http://v8.1c.ru/8.1/data/ui/colors/palette" xmlns:style="http://v8.1c.ru/8.1/data/ui/style" xmlns:sys="http://v8.1c.ru/8.1/data/ui/fonts/system" xmlns:web="http://v8.1c.ru/8.1/data/ui/colors/web" xmlns:win="http://v8.1c.ru/8.1/data/ui/colors/windows" xmlns:dcscor="http://v8.1c.ru/8.1/data-composition-system/core">
	<filter>
		<viewMode>Normal</viewMode>
		<userSettingID>dfcece9d-5077-440b-b6b3-45a5cb4538eb</userSettingID>
	</filter>
	<order>
		<viewMode>Normal</viewMode>
		<userSettingID>88619765-ccb3-46c6-ac52-38e9c992ebd4</userSettingID>
	</order>
	<conditionalAppearance>
		<viewMode>Normal</viewMode>
		<userSettingID>b75fecce-942b-4aed-abc9-e6a02e460fb3</userSettingID>
	</conditionalAppearance>
	<itemsViewMode>Normal</itemsViewMode>
	<itemsUserSettingID>911b6018-f537-43e8-a417-da56b22f9aec</itemsUserSettingID>
</Settings>
```

## FILE: src/Catalogs/Товары/Forms/ФормаСписка/Form.form
```xml
<?xml version="1.0" encoding="UTF-8"?>
<form:Form xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:form="http://g5.1c.ru/v8/dt/form">
  <items xsi:type="form:FormGroup">
    <name>СписокКомпоновщикНастроекПользовательскиеНастройки</name>
    <id>1</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <title>
      <key>ru</key>
      <value>Группа пользовательских настроек</value>
    </title>
    <verticalStretch>false</verticalStretch>
    <extendedTooltip>
      <name>СписокКомпоновщикНастроекПользовательскиеНастройкиРасширеннаяПодсказка</name>
      <id>2</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <type>UsualGroup</type>
    <extInfo xsi:type="form:UsualGroupExtInfo">
      <group>Vertical</group>
      <behavior>Auto</behavior>
      <representation>WeakSeparation</representation>
      <showLeftMargin>true</showLeftMargin>
      <united>true</united>
      <throughAlign>Auto</throughAlign>
      <currentRowUse>Auto</currentRowUse>
    </extInfo>
  </items>
  <items xsi:type="form:Table">
    <name>Список</name>
    <id>3</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Список</segments>
    </dataPath>
    <defaultItem>true</defaultItem>
    <titleLocation>None</titleLocation>
    <items xsi:type="form:FormField">
      <name>Артикул</name>
      <id>19</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Артикул</segments>
      </dataPath>
      <extendedTooltip>
        <name>АртикулРасширеннаяПодсказка</name>
        <id>21</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>АртикулКонтекстноеМеню</name>
        <id>20</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>Наименование</name>
      <id>16</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Description</segments>
      </dataPath>
      <defaultItem>true</defaultItem>
      <extendedTooltip>
        <name>НаименованиеРасширеннаяПодсказка</name>
        <id>18</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>НаименованиеКонтекстноеМеню</name>
        <id>17</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>Себестоимость</name>
      <id>22</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Себестоимость</segments>
      </dataPath>
      <extendedTooltip>
        <name>СебестоимостьРасширеннаяПодсказка</name>
        <id>24</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СебестоимостьКонтекстноеМеню</name>
        <id>23</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <autoCommandBar>
      <name>СписокКоманднаяПанель</name>
      <id>5</id>
      <horizontalAlign>Left</horizontalAlign>
      <autoFill>true</autoFill>
    </autoCommandBar>
    <searchStringAddition>
      <name>СписокСтрокаПоиска</name>
      <id>7</id>
      <extendedTooltip>
        <name>СписокСтрокаПоискаРасширеннаяПодсказка</name>
        <id>9</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСтрокаПоискаКонтекстноеМеню</name>
        <id>8</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <source>Список</source>
      <extInfo xsi:type="form:SearchStringAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchStringAddition>
    <viewStatusAddition>
      <name>СписокСостояниеПросмотра</name>
      <id>10</id>
      <extendedTooltip>
        <name>СписокСостояниеПросмотраРасширеннаяПодсказка</name>
        <id>12</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСостояниеПросмотраКонтекстноеМеню</name>
        <id>11</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>ViewStatusAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:ViewStatusAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </viewStatusAddition>
    <searchControlAddition>
      <name>СписокУправлениеПоиском</name>
      <id>13</id>
      <extendedTooltip>
        <name>СписокУправлениеПоискомРасширеннаяПодсказка</name>
        <id>15</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокУправлениеПоискомКонтекстноеМеню</name>
        <id>14</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>SearchControlAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:SearchControlAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchControlAddition>
    <extendedTooltip>
      <name>СписокРасширеннаяПодсказка</name>
      <id>6</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>СписокКонтекстноеМеню</name>
      <id>4</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <changeRowSet>true</changeRowSet>
    <changeRowOrder>true</changeRowOrder>
    <autoMaxWidth>true</autoMaxWidth>
    <autoMaxHeight>true</autoMaxHeight>
    <autoMaxRowsCount>true</autoMaxRowsCount>
    <selectionMode>MultiRow</selectionMode>
    <rowSelectionMode>Auto</rowSelectionMode>
    <header>true</header>
    <headerHeight>1</headerHeight>
    <footerHeight>1</footerHeight>
    <horizontalScrollBar>AutoUse</horizontalScrollBar>
    <verticalScrollBar>AutoUse</verticalScrollBar>
    <horizontalLines>true</horizontalLines>
    <verticalLines>true</verticalLines>
    <searchOnInput>Auto</searchOnInput>
    <initialListView>Auto</initialListView>
    <initialTreeView>ExpandTopLevel</initialTreeView>
    <initialRowActivation>Activate</initialRowActivation>
    <horizontalStretch>true</horizontalStretch>
    <verticalStretch>true</verticalStretch>
    <enableStartDrag>true</enableStartDrag>
    <fileDragMode>AsFileRef</fileDragMode>
    <rowPictureDataPath xsi:type="form:DataPath">
      <segments>Список.DefaultPicture</segments>
    </rowPictureDataPath>
    <autoMaxCardHeight>true</autoMaxCardHeight>
    <extInfo xsi:type="form:DynamicListTableExtInfo">
      <autoRefreshPeriod>60</autoRefreshPeriod>
      <period>
        <startDate>0001-01-01T00:00:00</startDate>
        <endDate>0001-01-01T00:00:00</endDate>
      </period>
      <topLevelParent xsi:type="core:UndefinedValue"/>
      <showRoot>true</showRoot>
      <allowGettingCurrentRowURL>true</allowGettingCurrentRowURL>
      <userSettingsGroup>СписокКомпоновщикНастроекПользовательскиеНастройки</userSettingsGroup>
    </extInfo>
    <showCommandBarNeedDereferenced>true</showCommandBarNeedDereferenced>
  </items>
  <autoCommandBar>
    <name>ФормаКоманднаяПанель</name>
    <id>-1</id>
    <horizontalAlign>Left</horizontalAlign>
    <autoFill>true</autoFill>
  </autoCommandBar>
  <saveWindowSettings>true</saveWindowSettings>
  <autoTitle>true</autoTitle>
  <autoUrl>true</autoUrl>
  <group>Auto</group>
  <autoFillCheck>true</autoFillCheck>
  <allowFormCustomize>true</allowFormCustomize>
  <enabled>true</enabled>
  <showTitle>auto</showTitle>
  <showCloseButton>true</showCloseButton>
  <attributes>
    <name>Список</name>
    <id>1</id>
    <valueType>
      <types>DynamicList</types>
    </valueType>
    <view>
      <common>true</common>
    </view>
    <edit>
      <common>true</common>
    </edit>
    <main>true</main>
    <extInfo xsi:type="form:DynamicListExtInfo">
      <mainTable>Catalog.Товары</mainTable>
      <dynamicDataRead>true</dynamicDataRead>
      <autoFillAvailableFields>true</autoFillAvailableFields>
      <autoSaveUserSettings>true</autoSaveUserSettings>
      <getInvisibleFieldPresentations>true</getInvisibleFieldPresentations>
    </extInfo>
  </attributes>
  <commandInterface>
    <navigationPanel/>
    <commandBar/>
  </commandInterface>
  <extInfo xsi:type="form:DynamicListFormExtInfo"/>
</form:Form>
```

## FILE: src/Catalogs/Товары/ObjectModule.bsl
```bsl

```

## FILE: src/Catalogs/Товары/Товары.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Catalog xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="970c0ccd-6a2f-419d-933e-ec844f028cec">
  <producedTypes>
    <objectType typeId="6bc45dac-a2e2-4164-9cec-92d335990534" valueTypeId="4803509f-4eae-49ec-b5e0-f7931c65dd4b"/>
    <refType typeId="460c9e34-82a8-43fe-8e42-b58f41417688" valueTypeId="59756ee6-89b6-4e82-8d42-e492eb1d3aeb"/>
    <selectionType typeId="63e8ec4b-4e6d-4fb0-b398-fbfe0b00b6cc" valueTypeId="782a1b1d-b7a6-48c5-9592-9a4da9a01a31"/>
    <listType typeId="aa4636b2-a82f-4fdb-a160-bc51fc1e88a2" valueTypeId="469c5bcb-0bb6-450d-a5b6-182a96826568"/>
    <managerType typeId="f0a25b97-ef3e-4cec-bcdf-0405c1fefd89" valueTypeId="0aed75f4-f3ab-4cf1-b7d5-ed4715a240cb"/>
  </producedTypes>
  <name>Товары</name>
  <synonym>
    <key>ru</key>
    <value>Товары</value>
  </synonym>
  <useStandardCommands>true</useStandardCommands>
  <inputByString>Catalog.Товары.StandardAttribute.Code</inputByString>
  <inputByString>Catalog.Товары.StandardAttribute.Description</inputByString>
  <fullTextSearchOnInputByString>DontUse</fullTextSearchOnInputByString>
  <createOnInput>Use</createOnInput>
  <dataLockControlMode>Managed</dataLockControlMode>
  <fullTextSearch>Use</fullTextSearch>
  <levelCount>2</levelCount>
  <foldersOnTop>true</foldersOnTop>
  <codeLength>9</codeLength>
  <descriptionLength>25</descriptionLength>
  <codeType>String</codeType>
  <codeAllowedLength>Variable</codeAllowedLength>
  <checkUnique>true</checkUnique>
  <autonumbering>true</autonumbering>
  <defaultPresentation>AsDescription</defaultPresentation>
  <editType>InDialog</editType>
  <choiceMode>BothWays</choiceMode>
  <defaultListForm>Catalog.Товары.Form.ФормаСписка</defaultListForm>
  <attributes uuid="5f3b3688-e99e-4629-82c8-69017ecd6f2e">
    <name>Артикул</name>
    <synonym>
      <key>ru</key>
      <value>Артикул</value>
    </synonym>
    <type>
      <types>String</types>
      <stringQualifiers>
        <length>10</length>
      </stringQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fillValue xsi:type="core:StringValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <dataHistory>Use</dataHistory>
  </attributes>
  <attributes uuid="740e073b-7a06-409e-9799-7cdd858f054f">
    <name>Себестоимость</name>
    <synonym>
      <key>ru</key>
      <value>Себестоимость</value>
    </synonym>
    <type>
      <types>Number</types>
      <numberQualifiers>
        <precision>15</precision>
        <scale>2</scale>
      </numberQualifiers>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fillValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <dataHistory>Use</dataHistory>
  </attributes>
  <forms uuid="9e95a83c-aa01-4e36-ab76-43c2b4178fa2">
    <name>ФормаСписка</name>
    <synonym>
      <key>ru</key>
      <value>Форма списка</value>
    </synonym>
    <usePurposes>PersonalComputer</usePurposes>
    <usePurposes>MobileDevice</usePurposes>
  </forms>
</mdclass:Catalog>
```

## FILE: src/Configuration/CommandInterface.cmi
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cmi:CommandInterface xmlns:cmi="http://g5.1c.ru/v8/dt/cmi"/>
```

## FILE: src/Configuration/Configuration.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Configuration xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="0ad97ec1-4288-4266-b92d-3afd2b952deb">
  <name>АгрегаторМаркетплейсов</name>
  <synonym>
    <key>ru</key>
    <value>Агрегатор маркетплейсов</value>
  </synonym>
  <containedObjects classId="9cd510cd-abfc-11d4-9434-004095e12fc7" objectId="0dd11314-b250-484f-ba89-39a0a0e0d0ec"/>
  <containedObjects classId="9fcd25a0-4822-11d4-9414-008048da11f9" objectId="0985050f-47d0-47fe-974a-f70a4f39c21e"/>
  <containedObjects classId="e3687481-0a87-462c-a166-9f34594f9bba" objectId="17f3c964-61d3-4c46-ae0d-4ab8fa5dbe3c"/>
  <containedObjects classId="9de14907-ec23-4a07-96f0-85521cb6b53b" objectId="eed056de-289a-4f9a-8e9e-f8f39600697e"/>
  <containedObjects classId="51f2d5d8-ea4d-4064-8892-82951750031e" objectId="bc2cd97e-f214-4b6f-b75b-32eaf6690b32"/>
  <containedObjects classId="e68182ea-4237-4383-967f-90c1e3370bc7" objectId="6e22750a-1783-4e99-bcc7-b0f551e059e2"/>
  <containedObjects classId="fb282519-d103-4dd3-bc12-cb271d631dfc" objectId="1172e2f6-dd95-4612-bc2c-e5d04fa5c882"/>
  <defaultRunMode>ManagedApplication</defaultRunMode>
  <usePurposes>PersonalComputer</usePurposes>
  <scriptVariant>Russian</scriptVariant>
  <usedMobileApplicationFunctionalities>
    <functionality>
      <use>true</use>
    </functionality>
    <functionality>
      <functionality>OSBackup</functionality>
      <use>true</use>
    </functionality>
  </usedMobileApplicationFunctionalities>
  <defaultLanguage>Language.Русский</defaultLanguage>
  <dataLockControlMode>Managed</dataLockControlMode>
  <objectAutonumerationMode>NotAutoFree</objectAutonumerationMode>
  <modalityUseMode>DontUse</modalityUseMode>
  <synchronousPlatformExtensionAndAddInCallUseMode>DontUse</synchronousPlatformExtensionAndAddInCallUseMode>
  <compatibilityMode>8.5.1</compatibilityMode>
  <languages uuid="07a16e7f-6363-4cd9-84cd-0ba5ee715011">
    <name>Русский</name>
    <synonym>
      <key>ru</key>
      <value>Русский</value>
    </synonym>
    <languageCode>ru</languageCode>
  </languages>
  <subsystems>Subsystem.Администрирование</subsystems>
  <subsystems>Subsystem.НСИ</subsystems>
  <subsystems>Subsystem.Отчеты</subsystems>
  <subsystems>Subsystem.Продажи</subsystems>
  <catalogs>Catalog.Контрагенты</catalogs>
  <catalogs>Catalog.Маркетплейсы</catalogs>
  <catalogs>Catalog.Товары</catalogs>
  <documents>Document.ОтчетОПродажахМаркетплейса</documents>
  <reports>Report.ДоходыПоТоварам</reports>
  <accumulationRegisters>AccumulationRegister.ПродажиМаркетплейсов</accumulationRegisters>
</mdclass:Configuration>
```

## FILE: src/Configuration/MainSectionCommandInterface.cmi
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cmi:CommandInterface xmlns:cmi="http://g5.1c.ru/v8/dt/cmi"/>
```

## FILE: src/Documents/ОтчетОПродажахМаркетплейса/Forms/ФормаДокумента/Form.form
```xml
<?xml version="1.0" encoding="UTF-8"?>
<form:Form xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:form="http://g5.1c.ru/v8/dt/form">
  <items xsi:type="form:FormField">
    <name>Дата</name>
    <id>4</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Объект.Date</segments>
    </dataPath>
    <extendedTooltip>
      <name>ДатаРасширеннаяПодсказка</name>
      <id>6</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>ДатаКонтекстноеМеню</name>
      <id>5</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <type>InputField</type>
    <editMode>EnterOnInput</editMode>
    <showInHeader>true</showInHeader>
    <headerHorizontalAlign>Left</headerHorizontalAlign>
    <showInFooter>true</showInFooter>
    <extInfo xsi:type="form:InputFieldExtInfo">
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <wrap>true</wrap>
      <extendedEditMultipleValues>true</extendedEditMultipleValues>
      <chooseType>true</chooseType>
      <typeDomainEnabled>true</typeDomainEnabled>
      <textEdit>true</textEdit>
      <textSize>Normal</textSize>
    </extInfo>
  </items>
  <items xsi:type="form:FormField">
    <name>Маркетплейс</name>
    <id>7</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Объект.Маркетплейс</segments>
    </dataPath>
    <handlers>
      <event>OnChange</event>
      <name>МаркетплейсПриИзменении</name>
    </handlers>
    <extendedTooltip>
      <name>МаркетплейсРасширеннаяПодсказка</name>
      <id>9</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>МаркетплейсКонтекстноеМеню</name>
      <id>8</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <type>InputField</type>
    <editMode>EnterOnInput</editMode>
    <showInHeader>true</showInHeader>
    <headerHorizontalAlign>Left</headerHorizontalAlign>
    <showInFooter>true</showInFooter>
    <extInfo xsi:type="form:InputFieldExtInfo">
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <wrap>true</wrap>
      <extendedEditMultipleValues>true</extendedEditMultipleValues>
      <chooseType>true</chooseType>
      <typeDomainEnabled>true</typeDomainEnabled>
      <textEdit>true</textEdit>
      <textSize>Normal</textSize>
    </extInfo>
  </items>
  <items xsi:type="form:Table">
    <name>Товары</name>
    <id>16</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Объект.Товары</segments>
    </dataPath>
    <titleLocation>None</titleLocation>
    <items xsi:type="form:FormField">
      <name>ТоварыНомерСтроки</name>
      <id>29</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.LineNumber</segments>
      </dataPath>
      <extendedTooltip>
        <name>ТоварыНомерСтрокиРасширеннаяПодсказка</name>
        <id>31</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыНомерСтрокиКонтекстноеМеню</name>
        <id>30</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыТовар</name>
      <id>32</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.Товар</segments>
      </dataPath>
      <handlers>
        <event>OnChange</event>
        <name>ТоварыТоварПриИзменении</name>
      </handlers>
      <extendedTooltip>
        <name>ТоварыТоварРасширеннаяПодсказка</name>
        <id>34</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыТоварКонтекстноеМеню</name>
        <id>33</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыКоличество</name>
      <id>35</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.Количество</segments>
      </dataPath>
      <handlers>
        <event>OnChange</event>
        <name>ТоварыКоличествоПриИзменении</name>
      </handlers>
      <extendedTooltip>
        <name>ТоварыКоличествоРасширеннаяПодсказка</name>
        <id>37</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыКоличествоКонтекстноеМеню</name>
        <id>36</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыЦенаПродажи</name>
      <id>38</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.ЦенаПродажи</segments>
      </dataPath>
      <handlers>
        <event>OnChange</event>
        <name>ТоварыЦенаПродажиПриИзменении</name>
      </handlers>
      <extendedTooltip>
        <name>ТоварыЦенаПродажиРасширеннаяПодсказка</name>
        <id>40</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыЦенаПродажиКонтекстноеМеню</name>
        <id>39</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыСуммаПродажи</name>
      <id>41</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.СуммаПродажи</segments>
      </dataPath>
      <extendedTooltip>
        <name>ТоварыСуммаПродажиРасширеннаяПодсказка</name>
        <id>43</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыСуммаПродажиКонтекстноеМеню</name>
        <id>42</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <readOnly>true</readOnly>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыКомиссия</name>
      <id>44</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.Комиссия</segments>
      </dataPath>
      <handlers>
        <event>OnChange</event>
        <name>ТоварыКомиссияПриИзменении</name>
      </handlers>
      <extendedTooltip>
        <name>ТоварыКомиссияРасширеннаяПодсказка</name>
        <id>46</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыКомиссияКонтекстноеМеню</name>
        <id>45</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыСебестоимость</name>
      <id>47</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.Себестоимость</segments>
      </dataPath>
      <extendedTooltip>
        <name>ТоварыСебестоимостьРасширеннаяПодсказка</name>
        <id>49</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыСебестоимостьКонтекстноеМеню</name>
        <id>48</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <readOnly>true</readOnly>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>ТоварыЧистаяПрибыль</name>
      <id>50</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Объект.Товары.ЧистаяПрибыль</segments>
      </dataPath>
      <extendedTooltip>
        <name>ТоварыЧистаяПрибыльРасширеннаяПодсказка</name>
        <id>52</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыЧистаяПрибыльКонтекстноеМеню</name>
        <id>51</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>InputField</type>
      <readOnly>true</readOnly>
      <editMode>EnterOnInput</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:InputFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <wrap>true</wrap>
        <extendedEditMultipleValues>true</extendedEditMultipleValues>
        <chooseType>true</chooseType>
        <typeDomainEnabled>true</typeDomainEnabled>
        <textEdit>true</textEdit>
        <textSize>Normal</textSize>
      </extInfo>
    </items>
    <autoCommandBar>
      <name>ТоварыКоманднаяПанель</name>
      <id>18</id>
      <horizontalAlign>Left</horizontalAlign>
      <autoFill>true</autoFill>
    </autoCommandBar>
    <searchStringAddition>
      <name>ТоварыСтрокаПоиска</name>
      <id>20</id>
      <extendedTooltip>
        <name>ТоварыСтрокаПоискаРасширеннаяПодсказка</name>
        <id>22</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыСтрокаПоискаКонтекстноеМеню</name>
        <id>21</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <source>Товары</source>
      <extInfo xsi:type="form:SearchStringAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchStringAddition>
    <viewStatusAddition>
      <name>ТоварыСостояниеПросмотра</name>
      <id>23</id>
      <extendedTooltip>
        <name>ТоварыСостояниеПросмотраРасширеннаяПодсказка</name>
        <id>25</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыСостояниеПросмотраКонтекстноеМеню</name>
        <id>24</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>ViewStatusAddition</type>
      <source>Товары</source>
      <extInfo xsi:type="form:ViewStatusAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </viewStatusAddition>
    <searchControlAddition>
      <name>ТоварыУправлениеПоиском</name>
      <id>26</id>
      <extendedTooltip>
        <name>ТоварыУправлениеПоискомРасширеннаяПодсказка</name>
        <id>28</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ТоварыУправлениеПоискомКонтекстноеМеню</name>
        <id>27</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>SearchControlAddition</type>
      <source>Товары</source>
      <extInfo xsi:type="form:SearchControlAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchControlAddition>
    <extendedTooltip>
      <name>ТоварыРасширеннаяПодсказка</name>
      <id>19</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>ТоварыКонтекстноеМеню</name>
      <id>17</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <changeRowSet>true</changeRowSet>
    <changeRowOrder>true</changeRowOrder>
    <autoMaxWidth>true</autoMaxWidth>
    <autoMaxHeight>true</autoMaxHeight>
    <autoMaxRowsCount>true</autoMaxRowsCount>
    <selectionMode>MultiRow</selectionMode>
    <rowSelectionMode>Auto</rowSelectionMode>
    <header>true</header>
    <headerHeight>1</headerHeight>
    <footerHeight>1</footerHeight>
    <horizontalScrollBar>AutoUse</horizontalScrollBar>
    <verticalScrollBar>AutoUse</verticalScrollBar>
    <horizontalLines>true</horizontalLines>
    <verticalLines>true</verticalLines>
    <autoInsertNewRow>true</autoInsertNewRow>
    <searchOnInput>Auto</searchOnInput>
    <initialListView>Auto</initialListView>
    <horizontalStretch>true</horizontalStretch>
    <verticalStretch>true</verticalStretch>
    <enableStartDrag>true</enableStartDrag>
    <enableDrag>true</enableDrag>
    <fileDragMode>AsFileRef</fileDragMode>
    <autoMaxCardHeight>true</autoMaxCardHeight>
    <rowFilter xsi:type="core:UndefinedValue"/>
    <showCommandBarNeedDereferenced>true</showCommandBarNeedDereferenced>
  </items>
  <autoCommandBar>
    <name>ФормаКоманднаяПанель</name>
    <id>-1</id>
    <horizontalAlign>Left</horizontalAlign>
    <autoFill>true</autoFill>
  </autoCommandBar>
  <saveWindowSettings>true</saveWindowSettings>
  <autoTitle>true</autoTitle>
  <autoUrl>true</autoUrl>
  <group>Auto</group>
  <autoFillCheck>true</autoFillCheck>
  <allowFormCustomize>true</allowFormCustomize>
  <enabled>true</enabled>
  <showTitle>auto</showTitle>
  <showCloseButton>true</showCloseButton>
  <attributes>
    <name>Объект</name>
    <id>1</id>
    <valueType>
      <types>DocumentObject.ОтчетОПродажахМаркетплейса</types>
    </valueType>
    <view>
      <common>true</common>
    </view>
    <edit>
      <common>true</common>
    </edit>
    <notDefaultUseAlwaysAttributes xsi:type="form:DataPath">
      <segments>Объект.RegisterRecords</segments>
    </notDefaultUseAlwaysAttributes>
    <main>true</main>
    <savedData>true</savedData>
  </attributes>
  <commandInterface>
    <navigationPanel/>
    <commandBar/>
  </commandInterface>
  <extInfo xsi:type="form:DocumentFormExtInfo">
    <repostOnWrite>true</repostOnWrite>
  </extInfo>
</form:Form>
```

## FILE: src/Documents/ОтчетОПродажахМаркетплейса/Forms/ФормаДокумента/Module.bsl
```bsl
&НаКлиенте
Процедура РассчитатьСтрокуТоваров(СтрокаТовары)

    Если СтрокаТовары = Неопределено Тогда
        Возврат;
    КонецЕсли;

    СтрокаТовары.СуммаПродажи = СтрокаТовары.Количество * СтрокаТовары.ЦенаПродажи;

    СебестоимостьЕдиницы = 0;

    Если ЗначениеЗаполнено(СтрокаТовары.Товар) Тогда
        СебестоимостьЕдиницы = ПолучитьСебестоимостьТовара(СтрокаТовары.Товар);
    КонецЕсли;

    СтрокаТовары.Себестоимость = СтрокаТовары.Количество * СебестоимостьЕдиницы;

    КомиссияПроцент = 0;

    Если ЗначениеЗаполнено(Объект.Маркетплейс) Тогда
        КомиссияПроцент = ПолучитьКомиссиюМаркетплейса(Объект.Маркетплейс);
    КонецЕсли;

    СтрокаТовары.Комиссия = Окр(СтрокаТовары.СуммаПродажи * КомиссияПроцент / 100, 2);

    СтрокаТовары.ЧистаяПрибыль = СтрокаТовары.СуммаПродажи
        - СтрокаТовары.Комиссия
        - СтрокаТовары.Себестоимость;

КонецПроцедуры

&НаКлиенте
Процедура МаркетплейсПриИзменении(Элемент)

    Для Каждого СтрокаТовары Из Объект.Товары Цикл
        РассчитатьСтрокуТоваров(СтрокаТовары);
    КонецЦикла;

КонецПроцедуры

&НаСервереБезКонтекста
Функция ПолучитьКомиссиюМаркетплейса(МаркетплейсСсылка)

    Если Не ЗначениеЗаполнено(МаркетплейсСсылка) Тогда
        Возврат 0;
    КонецЕсли;

    Возврат МаркетплейсСсылка.КомиссияПроцент;

КонецФункции

&НаСервереБезКонтекста
Функция ПолучитьСебестоимостьТовара(ТоварСсылка)

    Если Не ЗначениеЗаполнено(ТоварСсылка) Тогда
        Возврат 0;
    КонецЕсли;

    Возврат ТоварСсылка.Себестоимость;

КонецФункции


&НаКлиенте
Процедура ТоварыКоличествоПриИзменении(Элемент)

    ТекущаяСтрока = Элементы.Товары.ТекущиеДанные;
    РассчитатьСтрокуТоваров(ТекущаяСтрока);

КонецПроцедуры


&НаКлиенте
Процедура ТоварыЦенаПродажиПриИзменении(Элемент)

    ТекущаяСтрока = Элементы.Товары.ТекущиеДанные;
    РассчитатьСтрокуТоваров(ТекущаяСтрока);

КонецПроцедуры


&НаКлиенте
Процедура ТоварыКомиссияПриИзменении(Элемент)

    ТекущаяСтрока = Элементы.Товары.ТекущиеДанные;
    РассчитатьСтрокуТоваров(ТекущаяСтрока);

КонецПроцедуры
```

## FILE: src/Documents/ОтчетОПродажахМаркетплейса/Forms/ФормаСписка/Attributes/Список/ExtInfo/ListSettings.dcss
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Settings xmlns="http://v8.1c.ru/8.1/data-composition-system/settings" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xs="http://www.w3.org/2001/XMLSchema" xmlns:v8="http://v8.1c.ru/8.1/data/core" xmlns:v8ui="http://v8.1c.ru/8.1/data/ui" xmlns:pal="http://v8.1c.ru/8.1/data/ui/colors/palette" xmlns:style="http://v8.1c.ru/8.1/data/ui/style" xmlns:sys="http://v8.1c.ru/8.1/data/ui/fonts/system" xmlns:web="http://v8.1c.ru/8.1/data/ui/colors/web" xmlns:win="http://v8.1c.ru/8.1/data/ui/colors/windows" xmlns:dcscor="http://v8.1c.ru/8.1/data-composition-system/core">
	<filter>
		<viewMode>Normal</viewMode>
		<userSettingID>dfcece9d-5077-440b-b6b3-45a5cb4538eb</userSettingID>
	</filter>
	<order>
		<viewMode>Normal</viewMode>
		<userSettingID>88619765-ccb3-46c6-ac52-38e9c992ebd4</userSettingID>
	</order>
	<conditionalAppearance>
		<viewMode>Normal</viewMode>
		<userSettingID>b75fecce-942b-4aed-abc9-e6a02e460fb3</userSettingID>
	</conditionalAppearance>
	<itemsViewMode>Normal</itemsViewMode>
	<itemsUserSettingID>911b6018-f537-43e8-a417-da56b22f9aec</itemsUserSettingID>
</Settings>
```

## FILE: src/Documents/ОтчетОПродажахМаркетплейса/Forms/ФормаСписка/Form.form
```xml
<?xml version="1.0" encoding="UTF-8"?>
<form:Form xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:form="http://g5.1c.ru/v8/dt/form">
  <items xsi:type="form:FormGroup">
    <name>СписокКомпоновщикНастроекПользовательскиеНастройки</name>
    <id>1</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <title>
      <key>ru</key>
      <value>Группа пользовательских настроек</value>
    </title>
    <verticalStretch>false</verticalStretch>
    <extendedTooltip>
      <name>СписокКомпоновщикНастроекПользовательскиеНастройкиРасширеннаяПодсказка</name>
      <id>2</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <type>UsualGroup</type>
    <extInfo xsi:type="form:UsualGroupExtInfo">
      <group>Vertical</group>
      <behavior>Auto</behavior>
      <representation>WeakSeparation</representation>
      <showLeftMargin>true</showLeftMargin>
      <united>true</united>
      <throughAlign>Auto</throughAlign>
      <currentRowUse>Auto</currentRowUse>
    </extInfo>
  </items>
  <items xsi:type="form:Table">
    <name>Список</name>
    <id>3</id>
    <visible>true</visible>
    <enabled>true</enabled>
    <userVisible>
      <common>true</common>
    </userVisible>
    <dataPath xsi:type="form:DataPath">
      <segments>Список</segments>
    </dataPath>
    <defaultItem>true</defaultItem>
    <titleLocation>None</titleLocation>
    <items xsi:type="form:FormField">
      <name>Номер</name>
      <id>16</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Number</segments>
      </dataPath>
      <defaultItem>true</defaultItem>
      <extendedTooltip>
        <name>НомерРасширеннаяПодсказка</name>
        <id>18</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>НомерКонтекстноеМеню</name>
        <id>17</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <items xsi:type="form:FormField">
      <name>Дата</name>
      <id>19</id>
      <visible>true</visible>
      <enabled>true</enabled>
      <userVisible>
        <common>true</common>
      </userVisible>
      <dataPath xsi:type="form:DataPath">
        <segments>Список.Date</segments>
      </dataPath>
      <extendedTooltip>
        <name>ДатаРасширеннаяПодсказка</name>
        <id>21</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>ДатаКонтекстноеМеню</name>
        <id>20</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>LabelField</type>
      <editMode>Auto</editMode>
      <showInHeader>true</showInHeader>
      <headerHorizontalAlign>Left</headerHorizontalAlign>
      <showInFooter>true</showInFooter>
      <extInfo xsi:type="form:LabelFieldExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
      </extInfo>
    </items>
    <autoCommandBar>
      <name>СписокКоманднаяПанель</name>
      <id>5</id>
      <horizontalAlign>Left</horizontalAlign>
      <autoFill>true</autoFill>
    </autoCommandBar>
    <searchStringAddition>
      <name>СписокСтрокаПоиска</name>
      <id>7</id>
      <extendedTooltip>
        <name>СписокСтрокаПоискаРасширеннаяПодсказка</name>
        <id>9</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСтрокаПоискаКонтекстноеМеню</name>
        <id>8</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <source>Список</source>
      <extInfo xsi:type="form:SearchStringAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchStringAddition>
    <viewStatusAddition>
      <name>СписокСостояниеПросмотра</name>
      <id>10</id>
      <extendedTooltip>
        <name>СписокСостояниеПросмотраРасширеннаяПодсказка</name>
        <id>12</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокСостояниеПросмотраКонтекстноеМеню</name>
        <id>11</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>ViewStatusAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:ViewStatusAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </viewStatusAddition>
    <searchControlAddition>
      <name>СписокУправлениеПоиском</name>
      <id>13</id>
      <extendedTooltip>
        <name>СписокУправлениеПоискомРасширеннаяПодсказка</name>
        <id>15</id>
        <type>Label</type>
        <autoMaxWidth>true</autoMaxWidth>
        <autoMaxHeight>true</autoMaxHeight>
        <extInfo xsi:type="form:LabelDecorationExtInfo">
          <horizontalAlign>Left</horizontalAlign>
        </extInfo>
      </extendedTooltip>
      <contextMenu>
        <name>СписокУправлениеПоискомКонтекстноеМеню</name>
        <id>14</id>
        <autoFill>true</autoFill>
      </contextMenu>
      <type>SearchControlAddition</type>
      <source>Список</source>
      <extInfo xsi:type="form:SearchControlAdditionExtInfo">
        <autoMaxWidth>true</autoMaxWidth>
      </extInfo>
    </searchControlAddition>
    <extendedTooltip>
      <name>СписокРасширеннаяПодсказка</name>
      <id>6</id>
      <type>Label</type>
      <autoMaxWidth>true</autoMaxWidth>
      <autoMaxHeight>true</autoMaxHeight>
      <extInfo xsi:type="form:LabelDecorationExtInfo">
        <horizontalAlign>Left</horizontalAlign>
      </extInfo>
    </extendedTooltip>
    <contextMenu>
      <name>СписокКонтекстноеМеню</name>
      <id>4</id>
      <autoFill>true</autoFill>
    </contextMenu>
    <changeRowSet>true</changeRowSet>
    <changeRowOrder>true</changeRowOrder>
    <autoMaxWidth>true</autoMaxWidth>
    <autoMaxHeight>true</autoMaxHeight>
    <autoMaxRowsCount>true</autoMaxRowsCount>
    <selectionMode>MultiRow</selectionMode>
    <rowSelectionMode>Auto</rowSelectionMode>
    <header>true</header>
    <headerHeight>1</headerHeight>
    <footerHeight>1</footerHeight>
    <horizontalScrollBar>AutoUse</horizontalScrollBar>
    <verticalScrollBar>AutoUse</verticalScrollBar>
    <horizontalLines>true</horizontalLines>
    <verticalLines>true</verticalLines>
    <searchOnInput>Auto</searchOnInput>
    <initialListView>Auto</initialListView>
    <initialTreeView>ExpandTopLevel</initialTreeView>
    <initialRowActivation>Activate</initialRowActivation>
    <horizontalStretch>true</horizontalStretch>
    <verticalStretch>true</verticalStretch>
    <enableStartDrag>true</enableStartDrag>
    <fileDragMode>AsFileRef</fileDragMode>
    <rowPictureDataPath xsi:type="form:DataPath">
      <segments>Список.DefaultPicture</segments>
    </rowPictureDataPath>
    <autoMaxCardHeight>true</autoMaxCardHeight>
    <extInfo xsi:type="form:DynamicListTableExtInfo">
      <autoRefreshPeriod>60</autoRefreshPeriod>
      <period>
        <startDate>0001-01-01T00:00:00</startDate>
        <endDate>0001-01-01T00:00:00</endDate>
      </period>
      <topLevelParent xsi:type="core:UndefinedValue"/>
      <showRoot>true</showRoot>
      <allowGettingCurrentRowURL>true</allowGettingCurrentRowURL>
      <userSettingsGroup>СписокКомпоновщикНастроекПользовательскиеНастройки</userSettingsGroup>
    </extInfo>
    <showCommandBarNeedDereferenced>true</showCommandBarNeedDereferenced>
  </items>
  <autoCommandBar>
    <name>ФормаКоманднаяПанель</name>
    <id>-1</id>
    <horizontalAlign>Left</horizontalAlign>
    <autoFill>true</autoFill>
  </autoCommandBar>
  <saveWindowSettings>true</saveWindowSettings>
  <autoTitle>true</autoTitle>
  <autoUrl>true</autoUrl>
  <group>Auto</group>
  <autoFillCheck>true</autoFillCheck>
  <allowFormCustomize>true</allowFormCustomize>
  <enabled>true</enabled>
  <showTitle>auto</showTitle>
  <showCloseButton>true</showCloseButton>
  <attributes>
    <name>Список</name>
    <id>1</id>
    <valueType>
      <types>DynamicList</types>
    </valueType>
    <view>
      <common>true</common>
    </view>
    <edit>
      <common>true</common>
    </edit>
    <main>true</main>
    <extInfo xsi:type="form:DynamicListExtInfo">
      <mainTable>Document.ОтчетОПродажахМаркетплейса</mainTable>
      <dynamicDataRead>true</dynamicDataRead>
      <autoFillAvailableFields>true</autoFillAvailableFields>
      <autoSaveUserSettings>true</autoSaveUserSettings>
      <getInvisibleFieldPresentations>true</getInvisibleFieldPresentations>
    </extInfo>
  </attributes>
  <commandInterface>
    <navigationPanel/>
    <commandBar/>
  </commandInterface>
  <extInfo xsi:type="form:DynamicListFormExtInfo"/>
</form:Form>
```

## FILE: src/Documents/ОтчетОПродажахМаркетплейса/ObjectModule.bsl
```bsl
Процедура ОбработкаПроведения(Отказ, РежимПроведения)

    Если Не ЗначениеЗаполнено(Маркетплейс) Тогда
        Сообщить("Не выбран маркетплейс.");
        Отказ = Истина;
        Возврат;
    КонецЕсли;

    Движения.ПродажиМаркетплейсов.Записывать = Истина;

    Для Каждого СтрокаТовары Из Товары Цикл

        Если Не ЗначениеЗаполнено(СтрокаТовары.Товар) Тогда
            Сообщить("Не заполнен товар в строке документа.");
            Отказ = Истина;
            Возврат;
        КонецЕсли;

        Если СтрокаТовары.Количество <= 0 Тогда
            Сообщить("Количество должно быть больше нуля.");
            Отказ = Истина;
            Возврат;
        КонецЕсли;

		СуммаПродажи = СтрокаТовары.Количество * СтрокаТовары.ЦенаПродажи;
		СебестоимостьСтроки = СтрокаТовары.Количество * СтрокаТовары.Товар.Себестоимость;
		
		КомиссияПроцент = Маркетплейс.КомиссияПроцент;
		КомиссияСтроки = Окр(СуммаПродажи * КомиссияПроцент / 100, 2);
		
		ЧистаяПрибыльСтроки = СуммаПродажи - КомиссияСтроки - СебестоимостьСтроки;
		
		Движение = Движения.ПродажиМаркетплейсов.Добавить();
		
		Движение.Период = Дата;
		Движение.Товар = СтрокаТовары.Товар;
		Движение.Маркетплейс = Маркетплейс;
		
		Движение.Количество = СтрокаТовары.Количество;
		Движение.СуммаПродажи = СуммаПродажи;
		Движение.СуммаКомиссии = КомиссияСтроки;
		Движение.Себестоимость = СебестоимостьСтроки;
		Движение.ЧистаяПрибыль = ЧистаяПрибыльСтроки;

    КонецЦикла;

КонецПроцедуры
```

## FILE: src/Documents/ОтчетОПродажахМаркетплейса/ОтчетОПродажахМаркетплейса.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Document xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://g5.1c.ru/v8/dt/mcore" xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="a2b4fc3e-4030-4db3-9d5d-6f35e45b9a24">
  <producedTypes>
    <objectType typeId="c92ecd6b-f84e-4ed7-8fe6-facfabf133ca" valueTypeId="297bca10-3c7e-495e-aa5c-8743cb9c102b"/>
    <refType typeId="edeaa904-093c-4f06-81a5-fa1ab2fc2031" valueTypeId="189cb2bc-a548-4f97-a3c6-e39a3c4d6b1e"/>
    <selectionType typeId="4d63ca6e-825b-4803-bb09-c4b8bce2f190" valueTypeId="13ab37d8-5514-461c-b815-d3daacc07213"/>
    <listType typeId="0f852c89-7385-495a-8b56-b29d41a55335" valueTypeId="85ec6001-1f7b-4e2a-920e-48c0040bbf08"/>
    <managerType typeId="e2b03455-f8f0-43ad-9706-4ac9c704c02e" valueTypeId="13a69ca3-6133-4fac-95c2-436776a1f0cb"/>
  </producedTypes>
  <name>ОтчетОПродажахМаркетплейса</name>
  <synonym>
    <key>ru</key>
    <value>Отчет о продажах маркетплейса</value>
  </synonym>
  <useStandardCommands>true</useStandardCommands>
  <inputByString>Document.ОтчетОПродажахМаркетплейса.StandardAttribute.Number</inputByString>
  <fullTextSearchOnInputByString>DontUse</fullTextSearchOnInputByString>
  <createOnInput>Use</createOnInput>
  <dataLockControlMode>Managed</dataLockControlMode>
  <fullTextSearch>Use</fullTextSearch>
  <numberType>String</numberType>
  <numberLength>9</numberLength>
  <numberAllowedLength>Variable</numberAllowedLength>
  <checkUnique>true</checkUnique>
  <autonumbering>true</autonumbering>
  <defaultObjectForm>Document.ОтчетОПродажахМаркетплейса.Form.ФормаДокумента</defaultObjectForm>
  <defaultListForm>Document.ОтчетОПродажахМаркетплейса.Form.ФормаСписка</defaultListForm>
  <registerRecords>AccumulationRegister.ПродажиМаркетплейсов</registerRecords>
  <postInPrivilegedMode>true</postInPrivilegedMode>
  <unpostInPrivilegedMode>true</unpostInPrivilegedMode>
  <attributes uuid="11358377-457e-4861-acd4-758cff467a9c">
    <name>Маркетплейс</name>
    <synonym>
      <key>ru</key>
      <value>Маркетплейс</value>
    </synonym>
    <type>
      <types>CatalogRef.Маркетплейсы</types>
    </type>
    <minValue xsi:type="core:UndefinedValue"/>
    <maxValue xsi:type="core:UndefinedValue"/>
    <fillValue xsi:type="core:UndefinedValue"/>
    <fullTextSearch>Use</fullTextSearch>
    <dataHistory>Use</dataHistory>
  </attributes>
  <forms uuid="ed67eae2-de6c-4e79-9fcb-8dd8b0520e43">
    <name>ФормаДокумента</name>
    <synonym>
      <key>ru</key>
      <value>Форма документа</value>
    </synonym>
    <usePurposes>PersonalComputer</usePurposes>
    <usePurposes>MobileDevice</usePurposes>
  </forms>
  <forms uuid="22c5a336-9758-4376-969f-4a05083daae7">
    <name>ФормаСписка</name>
    <synonym>
      <key>ru</key>
      <value>Форма списка</value>
    </synonym>
    <usePurposes>PersonalComputer</usePurposes>
    <usePurposes>MobileDevice</usePurposes>
  </forms>
  <tabularSections uuid="fbed294d-6cad-4ce2-a878-198de746028b">
    <producedTypes>
      <objectType typeId="4a026bf2-63f6-456a-ae96-f7e853ba3fb8" valueTypeId="69b963f8-13da-43db-8169-81f79919cf6b"/>
      <rowType typeId="fded4d1c-f55d-4cba-b284-a1d772c86f6f" valueTypeId="f06316f8-987d-4a5d-8dc6-5f03687c7796"/>
    </producedTypes>
    <name>Товары</name>
    <synonym>
      <key>ru</key>
      <value>Товары</value>
    </synonym>
    <attributes uuid="83fcbda9-defb-4edd-b4c6-1f10506a82a4">
      <name>Товар</name>
      <synonym>
        <key>ru</key>
        <value>Товар</value>
      </synonym>
      <type>
        <types>CatalogRef.Товары</types>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <attributes uuid="94c8ad5a-111c-4067-bdb4-4a26b33d0bdb">
      <name>Количество</name>
      <synonym>
        <key>ru</key>
        <value>Количество</value>
      </synonym>
      <type>
        <types>Number</types>
        <numberQualifiers>
          <precision>15</precision>
          <scale>3</scale>
        </numberQualifiers>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <attributes uuid="635bba63-7c9d-4690-b4fc-873d85148855">
      <name>ЦенаПродажи</name>
      <synonym>
        <key>ru</key>
        <value>Цена продажи</value>
      </synonym>
      <type>
        <types>Number</types>
        <numberQualifiers>
          <precision>15</precision>
          <scale>2</scale>
        </numberQualifiers>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <attributes uuid="3fbc1dfd-ca36-4d15-9974-041730f3c2d7">
      <name>СуммаПродажи</name>
      <synonym>
        <key>ru</key>
        <value>Сумма продажи</value>
      </synonym>
      <type>
        <types>Number</types>
        <numberQualifiers>
          <precision>15</precision>
          <scale>2</scale>
        </numberQualifiers>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <attributes uuid="290d1205-ed14-44d5-b311-b83b7441edfe">
      <name>Комиссия</name>
      <synonym>
        <key>ru</key>
        <value>Комиссия</value>
      </synonym>
      <type>
        <types>Number</types>
        <numberQualifiers>
          <precision>15</precision>
          <scale>2</scale>
        </numberQualifiers>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <attributes uuid="c08a06eb-4bd3-4cd2-89a0-1275779ca844">
      <name>Себестоимость</name>
      <synonym>
        <key>ru</key>
        <value>Себестоимость</value>
      </synonym>
      <type>
        <types>Number</types>
        <numberQualifiers>
          <precision>15</precision>
          <scale>2</scale>
        </numberQualifiers>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <attributes uuid="d90310f2-8c94-4a6e-b4b4-8e7bc8eea9ba">
      <name>ЧистаяПрибыль</name>
      <synonym>
        <key>ru</key>
        <value>Чистая прибыль</value>
      </synonym>
      <type>
        <types>Number</types>
        <numberQualifiers>
          <precision>15</precision>
          <scale>2</scale>
        </numberQualifiers>
      </type>
      <minValue xsi:type="core:UndefinedValue"/>
      <maxValue xsi:type="core:UndefinedValue"/>
      <dataHistory>Use</dataHistory>
      <fullTextSearch>Use</fullTextSearch>
    </attributes>
    <lineNumberLength>9</lineNumberLength>
  </tabularSections>
</mdclass:Document>
```

## FILE: src/Reports/ДоходыПоТоварам/ManagerModule.bsl
```bsl

```

## FILE: src/Reports/ДоходыПоТоварам/ObjectModule.bsl
```bsl

```

## FILE: src/Reports/ДоходыПоТоварам/Templates/СКД/Template.dcs
```xml
<?xml version="1.0" encoding="UTF-8"?>
<DataCompositionSchema xmlns="http://v8.1c.ru/8.1/data-composition-system/schema" xmlns:dcscom="http://v8.1c.ru/8.1/data-composition-system/common" xmlns:dcscor="http://v8.1c.ru/8.1/data-composition-system/core" xmlns:dcsset="http://v8.1c.ru/8.1/data-composition-system/settings" xmlns:v8="http://v8.1c.ru/8.1/data/core" xmlns:v8ui="http://v8.1c.ru/8.1/data/ui" xmlns:xs="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<dataSource>
		<name>ИсточникДанных1</name>
		<dataSourceType>Local</dataSourceType>
	</dataSource>
	<dataSet xsi:type="DataSetQuery">
		<name>НаборДанных1</name>
		<field xsi:type="DataSetFieldField">
			<dataPath>Товар</dataPath>
			<field>Товар</field>
			<role>
				<dcscom:dimension>true</dcscom:dimension>
			</role>
		</field>
		<field xsi:type="DataSetFieldField">
			<dataPath>Маркетплейс</dataPath>
			<field>Маркетплейс</field>
			<role>
				<dcscom:dimension>true</dcscom:dimension>
			</role>
		</field>
		<field xsi:type="DataSetFieldField">
			<dataPath>Количество</dataPath>
			<field>Количество</field>
			<title xsi:type="v8:LocalStringType">
				<v8:item>
					<v8:lang>ru</v8:lang>
					<v8:content>Количество</v8:content>
				</v8:item>
			</title>
		</field>
		<field xsi:type="DataSetFieldField">
			<dataPath>СуммаПродажи</dataPath>
			<field>СуммаПродажи</field>
			<title xsi:type="v8:LocalStringType">
				<v8:item>
					<v8:lang>ru</v8:lang>
					<v8:content>Сумма продажи</v8:content>
				</v8:item>
			</title>
		</field>
		<field xsi:type="DataSetFieldField">
			<dataPath>СуммаКомиссии</dataPath>
			<field>СуммаКомиссии</field>
			<title xsi:type="v8:LocalStringType">
				<v8:item>
					<v8:lang>ru</v8:lang>
					<v8:content>Сумма комиссии</v8:content>
				</v8:item>
			</title>
		</field>
		<field xsi:type="DataSetFieldField">
			<dataPath>Себестоимость</dataPath>
			<field>Себестоимость</field>
			<title xsi:type="v8:LocalStringType">
				<v8:item>
					<v8:lang>ru</v8:lang>
					<v8:content>Себестоимость</v8:content>
				</v8:item>
			</title>
		</field>
		<field xsi:type="DataSetFieldField">
			<dataPath>ЧистаяПрибыль</dataPath>
			<field>ЧистаяПрибыль</field>
			<title xsi:type="v8:LocalStringType">
				<v8:item>
					<v8:lang>ru</v8:lang>
					<v8:content>Чистая прибыль</v8:content>
				</v8:item>
			</title>
		</field>
		<dataSource>ИсточникДанных1</dataSource>
		<query>ВЫБРАТЬ
    ПродажиОбороты.Товар КАК Товар,
    ПродажиОбороты.Маркетплейс КАК Маркетплейс,
    ПродажиОбороты.КоличествоОборот КАК Количество,
    ПродажиОбороты.СуммаПродажиОборот КАК СуммаПродажи,
    ПродажиОбороты.СуммаКомиссииОборот КАК СуммаКомиссии,
    ПродажиОбороты.СебестоимостьОборот КАК Себестоимость,
    ПродажиОбороты.ЧистаяПрибыльОборот КАК ЧистаяПрибыль
ИЗ
    РегистрНакопления.ПродажиМаркетплейсов.Обороты(
        &amp;НачалоПериода,
        &amp;КонецПериода,
        ,
    ) КАК ПродажиОбороты</query>
	</dataSet>
	<totalField>
		<dataPath>Количество</dataPath>
		<expression>Сумма(Количество)</expression>
	</totalField>
	<totalField>
		<dataPath>СуммаПродажи</dataPath>
		<expression>Сумма(СуммаПродажи)</expression>
	</totalField>
	<totalField>
		<dataPath>СуммаКомиссии</dataPath>
		<expression>Сумма(СуммаКомиссии)</expression>
	</totalField>
	<totalField>
		<dataPath>Себестоимость</dataPath>
		<expression>Сумма(Себестоимость)</expression>
	</totalField>
	<totalField>
		<dataPath>ЧистаяПрибыль</dataPath>
		<expression>Сумма(ЧистаяПрибыль)</expression>
	</totalField>
	<parameter>
		<name>НачалоПериода</name>
		<title xsi:type="v8:LocalStringType">
			<v8:item>
				<v8:lang>ru</v8:lang>
				<v8:content>Начало периода</v8:content>
			</v8:item>
		</title>
		<valueType>
			<v8:Type>xs:dateTime</v8:Type>
			<v8:DateQualifiers>
				<v8:DateFractions>DateTime</v8:DateFractions>
			</v8:DateQualifiers>
		</valueType>
		<useRestriction>false</useRestriction>
		<use>Always</use>
	</parameter>
	<parameter>
		<name>КонецПериода</name>
		<title xsi:type="v8:LocalStringType">
			<v8:item>
				<v8:lang>ru</v8:lang>
				<v8:content>Конец периода</v8:content>
			</v8:item>
		</title>
		<valueType>
			<v8:Type>xs:dateTime</v8:Type>
			<v8:DateQualifiers>
				<v8:DateFractions>DateTime</v8:DateFractions>
			</v8:DateQualifiers>
		</valueType>
		<useRestriction>false</useRestriction>
		<availableAsField>false</availableAsField>
		<use>Always</use>
	</parameter>
	<settingsVariant>
		<dcsset:name>Основной</dcsset:name>
		<dcsset:presentation xsi:type="xs:string">Основной</dcsset:presentation>
		<dcsset:settings xmlns:pal="http://v8.1c.ru/8.1/data/ui/colors/palette" xmlns:style="http://v8.1c.ru/8.1/data/ui/style" xmlns:sys="http://v8.1c.ru/8.1/data/ui/fonts/system" xmlns:web="http://v8.1c.ru/8.1/data/ui/colors/web" xmlns:win="http://v8.1c.ru/8.1/data/ui/colors/windows">
			<dcsset:selection>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>Товар</dcsset:field>
				</dcsset:item>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>Маркетплейс</dcsset:field>
				</dcsset:item>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>Количество</dcsset:field>
				</dcsset:item>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>СуммаПродажи</dcsset:field>
				</dcsset:item>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>СуммаКомиссии</dcsset:field>
				</dcsset:item>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>Себестоимость</dcsset:field>
				</dcsset:item>
				<dcsset:item xsi:type="dcsset:SelectedItemField">
					<dcsset:field>ЧистаяПрибыль</dcsset:field>
				</dcsset:item>
			</dcsset:selection>
			<dcsset:dataParameters>
				<dcscor:item xsi:type="dcsset:SettingsParameterValue">
					<dcscor:parameter>НачалоПериода</dcscor:parameter>
				</dcscor:item>
				<dcscor:item xsi:type="dcsset:SettingsParameterValue">
					<dcscor:parameter>КонецПериода</dcscor:parameter>
				</dcscor:item>
			</dcsset:dataParameters>
			<dcsset:item xsi:type="dcsset:StructureItemGroup">
				<dcsset:groupItems>
					<dcsset:item xsi:type="dcsset:GroupItemField">
						<dcsset:field>Товар</dcsset:field>
						<dcsset:groupType>Items</dcsset:groupType>
						<dcsset:periodAdditionType>None</dcsset:periodAdditionType>
					</dcsset:item>
				</dcsset:groupItems>
				<dcsset:order>
					<dcsset:item xsi:type="dcsset:OrderItemAuto"/>
				</dcsset:order>
				<dcsset:selection>
					<dcsset:item xsi:type="dcsset:SelectedItemAuto"/>
				</dcsset:selection>
				<dcsset:item xsi:type="dcsset:StructureItemGroup">
					<dcsset:groupItems>
						<dcsset:item xsi:type="dcsset:GroupItemField">
							<dcsset:field>Маркетплейс</dcsset:field>
							<dcsset:groupType>Items</dcsset:groupType>
							<dcsset:periodAdditionType>None</dcsset:periodAdditionType>
						</dcsset:item>
					</dcsset:groupItems>
					<dcsset:order>
						<dcsset:item xsi:type="dcsset:OrderItemAuto"/>
					</dcsset:order>
					<dcsset:selection>
						<dcsset:item xsi:type="dcsset:SelectedItemAuto"/>
					</dcsset:selection>
				</dcsset:item>
			</dcsset:item>
		</dcsset:settings>
	</settingsVariant>
</DataCompositionSchema>
```

## FILE: src/Reports/ДоходыПоТоварам/ДоходыПоТоварам.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Report xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="5f0c5b09-62a1-4b08-9c36-eddc4306bc53">
  <producedTypes>
    <objectType typeId="d8632a92-ee85-424f-8c2f-0e1d44a2d1aa" valueTypeId="494faeac-c7ef-482a-b33a-0ccadc1f011a"/>
    <managerType typeId="6487622c-6f1f-4495-aa5d-49ba112c7700" valueTypeId="72a5639a-335f-4b12-be38-59fa3ac7075e"/>
  </producedTypes>
  <name>ДоходыПоТоварам</name>
  <synonym>
    <key>ru</key>
    <value>Доходы по товарам</value>
  </synonym>
  <useStandardCommands>true</useStandardCommands>
  <mainDataCompositionSchema>Report.ДоходыПоТоварам.Template.СКД</mainDataCompositionSchema>
  <templates uuid="43f4cecb-149b-46bc-be22-0783ceb63ac9">
    <name>СКД</name>
    <synonym>
      <key>ru</key>
      <value>СКД</value>
    </synonym>
    <templateType>DataCompositionSchema</templateType>
  </templates>
</mdclass:Report>
```

## FILE: src/Subsystems/Администрирование/CommandInterface.cmi
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cmi:CommandInterface xmlns:cmi="http://g5.1c.ru/v8/dt/cmi"/>
```

## FILE: src/Subsystems/Администрирование/Администрирование.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Subsystem xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="90c33072-0326-4d11-b2e9-d9dc0bd9ba3c">
  <name>Администрирование</name>
  <synonym>
    <key>ru</key>
    <value>Администрирование</value>
  </synonym>
  <includeHelpInContents>true</includeHelpInContents>
  <includeInCommandInterface>true</includeInCommandInterface>
</mdclass:Subsystem>
```

## FILE: src/Subsystems/НСИ/CommandInterface.cmi
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cmi:CommandInterface xmlns:cmi="http://g5.1c.ru/v8/dt/cmi"/>
```

## FILE: src/Subsystems/НСИ/НСИ.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Subsystem xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="1274079a-83cd-4558-88c8-ff69a096ebad">
  <name>НСИ</name>
  <synonym>
    <key>ru</key>
    <value>НСИ</value>
  </synonym>
  <includeHelpInContents>true</includeHelpInContents>
  <includeInCommandInterface>true</includeInCommandInterface>
  <content>Catalog.Товары</content>
  <content>Catalog.Маркетплейсы</content>
  <content>Catalog.Контрагенты</content>
</mdclass:Subsystem>
```

## FILE: src/Subsystems/Отчеты/CommandInterface.cmi
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cmi:CommandInterface xmlns:cmi="http://g5.1c.ru/v8/dt/cmi"/>
```

## FILE: src/Subsystems/Отчеты/Отчеты.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Subsystem xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="f871d1fc-1739-4df3-8300-bf7a2aef4644">
  <name>Отчеты</name>
  <synonym>
    <key>ru</key>
    <value>Отчеты</value>
  </synonym>
  <includeHelpInContents>true</includeHelpInContents>
  <includeInCommandInterface>true</includeInCommandInterface>
  <content>Report.ДоходыПоТоварам</content>
</mdclass:Subsystem>
```

## FILE: src/Subsystems/Продажи/CommandInterface.cmi
```xml
<?xml version="1.0" encoding="UTF-8"?>
<cmi:CommandInterface xmlns:cmi="http://g5.1c.ru/v8/dt/cmi"/>
```

## FILE: src/Subsystems/Продажи/Продажи.mdo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdclass:Subsystem xmlns:mdclass="http://g5.1c.ru/v8/dt/metadata/mdclass" uuid="60613ea5-ab6d-4bf6-8ce7-203356c56cd4">
  <name>Продажи</name>
  <synonym>
    <key>ru</key>
    <value>Продажи</value>
  </synonym>
  <includeHelpInContents>true</includeHelpInContents>
  <includeInCommandInterface>true</includeInCommandInterface>
  <content>Document.ОтчетОПродажахМаркетплейса</content>
</mdclass:Subsystem>
```
