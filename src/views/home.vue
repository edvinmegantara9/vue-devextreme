<template>
  <div>
    <h2 class="content-block">Home</h2>
    <div class="content-block">
      <div class="dx-card responsive-paddings">
        <div class="logos-container">
          <h2>Halo Dunia</h2>
        </div>

        <p>Thanks for using the DevExtreme Vue App Template.</p>
        <p>
          This application was built using
          <a
            href="https://cli.vuejs.org/"
            target="_blank"
            rel="noopener noreferrer"
            >Vue CLI</a
          >
          and
          <a
            href="https://js.devexpress.com/Documentation/Guide/Common/DevExtreme_CLI/"
            target="_blank"
            rel="noopener noreferrer"
            >DevExtreme CLI</a
          >
          and includes the following DevExtreme components:
        </p>
        <ul>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Widgets/DataGrid/Overview/"
              target="_blank"
              rel="noopener noreferrer"
              >DataGrid</a
            >
          </li>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Widgets/Form/Overview/"
              target="_blank"
              rel="noopener noreferrer"
              >Form</a
            >
          </li>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Widgets/Drawer/Getting_Started_with_Navigation_Drawer/"
              target="_blank"
              rel="noopener noreferrer"
              >Drawer</a
            >
          </li>
        </ul>

        <p>
          To customize your DevExtreme Vue application further, please refer to
          the following help topics:
        </p>

        <ul>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Vue_Components/Create_a_DevExtreme_Application/#Layouts"
              target="_blank"
              rel="noopener noreferrer"
              >Layouts</a
            >
          </li>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Vue_Components/Create_a_DevExtreme_Application/#Add_a_New_View"
              target="_blank"
              rel="noopener noreferrer"
              >Add a New View</a
            >
          </li>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Vue_Components/Create_a_DevExtreme_Application/#Configure_the_Navigation_Menu"
              target="_blank"
              rel="noopener noreferrer"
              >Configure the Navigation Menu</a
            >
          </li>
          <li>
            <a
              href="https://js.devexpress.com/Documentation/Guide/Vue_Components/Create_a_DevExtreme_Application/#Configure_Themes"
              target="_blank"
              rel="noopener noreferrer"
              >Configure Themes</a
            >
          </li>
        </ul>
        <p>
          For technical content related to DevExtreme Vue components, feel free
          to explore our
          <a
            href="https://js.devexpress.com/documentation/"
            target="_blank"
            rel="noopener noreferrer"
            >online documentation</a
          >
          and
          <a
            href="https://js.devexpress.com/Demos/Widgetsgallery/"
            target="_blank"
            rel="noopener noreferrer"
            >technical demos</a
          >.
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.logos-container {
  margin: 20px 0 40px 0;
  text-align: center;
  svg {
    display: inline-block;
  }
}

.devextreme-logo {
  width: 200px;
  height: 34px;
  margin-bottom: 17px;
}

.vue-logo {
  width: 180px;
  height: 62px;
}

.plus {
  margin: 20px 10px;
  width: 22px;
  height: 22px;
}

.screen-x-small .logos-container {
  svg {
    width: 100%;
    display: block;
    &.plus {
      margin: 0;
    }
  }
}
</style>
