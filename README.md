# tela-cadastro-de-produtos
interface
<?xml version="1.0" encoding="UTF-8"?>
<ui version="4.0">
 <class>MainWindow</class>
 <widget class="QMainWindow" name="MainWindow">
  <property name="geometry">
   <rect>
    <x>0</x>
    <y>0</y>
    <width>548</width>
    <height>553</height>
   </rect>
  </property>
  <property name="windowTitle">
   <string>MainWindow</string>
  </property>
  <property name="styleSheet">
   <string notr="true">background-color: rgb(0, 255, 127);</string>
  </property>
  <widget class="QWidget" name="centralwidget">
   <widget class="QLabel" name="label">
    <property name="geometry">
     <rect>
      <x>120</x>
      <y>10</y>
      <width>301</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>20</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Cadastro de Produtos</string>
    </property>
   </widget>
   <widget class="QLabel" name="label_2">
    <property name="geometry">
     <rect>
      <x>80</x>
      <y>110</y>
      <width>101</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>15</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Código</string>
    </property>
   </widget>
   <widget class="QLabel" name="label_3">
    <property name="geometry">
     <rect>
      <x>80</x>
      <y>160</y>
      <width>101</width>
      <height>41</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>15</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Descrição</string>
    </property>
   </widget>
   <widget class="QLabel" name="label_4">
    <property name="geometry">
     <rect>
      <x>80</x>
      <y>210</y>
      <width>71</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>15</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Preço</string>
    </property>
   </widget>
   <widget class="QLineEdit" name="lineEdit">
    <property name="geometry">
     <rect>
      <x>200</x>
      <y>110</y>
      <width>211</width>
      <height>31</height>
     </rect>
    </property>
    <property name="styleSheet">
     <string notr="true">background-color: rgb(255, 255, 255);</string>
    </property>
    <property name="text">
     <string/>
    </property>
   </widget>
   <widget class="QLineEdit" name="lineEdit_2">
    <property name="geometry">
     <rect>
      <x>200</x>
      <y>160</y>
      <width>211</width>
      <height>31</height>
     </rect>
    </property>
    <property name="styleSheet">
     <string notr="true">background-color: rgb(255, 255, 255);</string>
    </property>
   </widget>
   <widget class="QLineEdit" name="lineEdit_3">
    <property name="geometry">
     <rect>
      <x>200</x>
      <y>210</y>
      <width>211</width>
      <height>31</height>
     </rect>
    </property>
    <property name="styleSheet">
     <string notr="true">background-color: rgb(255, 255, 255);</string>
    </property>
   </widget>
   <widget class="QRadioButton" name="radioButton">
    <property name="geometry">
     <rect>
      <x>300</x>
      <y>310</y>
      <width>141</width>
      <height>21</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Informática</string>
    </property>
   </widget>
   <widget class="QRadioButton" name="radioButton_2">
    <property name="geometry">
     <rect>
      <x>300</x>
      <y>340</y>
      <width>121</width>
      <height>21</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Alimentos</string>
    </property>
   </widget>
   <widget class="QRadioButton" name="radioButton_3">
    <property name="geometry">
     <rect>
      <x>300</x>
      <y>370</y>
      <width>131</width>
      <height>21</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Eletrônicos</string>
    </property>
   </widget>
   <widget class="QLabel" name="label_5">
    <property name="geometry">
     <rect>
      <x>200</x>
      <y>280</y>
      <width>111</width>
      <height>21</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="text">
     <string>Categorias:</string>
    </property>
   </widget>
   <widget class="QPushButton" name="pushButton">
    <property name="geometry">
     <rect>
      <x>230</x>
      <y>450</y>
      <width>91</width>
      <height>31</height>
     </rect>
    </property>
    <property name="font">
     <font>
      <pointsize>12</pointsize>
      <weight>75</weight>
      <bold>true</bold>
     </font>
    </property>
    <property name="styleSheet">
     <string notr="true">background-color: rgb(0, 85, 255);</string>
    </property>
    <property name="text">
     <string>Enviar</string>
    </property>
   </widget>
  </widget>
  <widget class="QMenuBar" name="menubar">
   <property name="geometry">
    <rect>
     <x>0</x>
     <y>0</y>
     <width>548</width>
     <height>21</height>
    </rect>
   </property>
  </widget>
  <widget class="QStatusBar" name="statusbar"/>
 </widget>
 <resources/>
 <connections/>
</ui>
****
