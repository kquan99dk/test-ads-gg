<template>
  <div>
    <h1>shop Pr trend hot tiktok google xu huong</h1>
    <h2>shop Pr trend hot tiktok google xu huong</h2>
    <h3>shop Pr trend hot tiktok google xu huong</h3>
    <h4>shop Pr trend hot tiktok google xu huong</h4>
    <h5>shop Pr trend hot tiktok google xu huong</h5>
    <!-- <div class="ct-select">
      <v-menu rounded="rounded" offset-y>
        <template v-slot:activator="{ attrs, on }">
          <v-btn color="primary" class="white--text ma-5" v-bind="attrs" v-on="on" width="300">
            <template>
              <div class="btn-ct d-flex justify-space-between">
                <div>
                  <v-icon>mdi-map</v-icon>
                  Radius
                </div>
                <v-icon class="icon-dropdown">mdi-map</v-icon>
              </div>
            </template>
          </v-btn>
        </template>

        <v-list>
          <v-list-item link>
            <v-list-item-title>
              đassdasd
            </v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </div> -->

    <div class="pr-ads">
      <adsbygoogle ad-slot="9232286674" />
    </div>
    <img width="200px" height="200px"  src="https://avi.edu.vn/wp-content/uploads/2019/11/london-2393098.jpg" alt="pari">
    <img width="200px" height="200px"  src="https://vuongquocanh.com/wp-content/uploads/2018/05/london-eye-800x534.jpg" alt="shop">
    <div class="footer mt-5">
      <v-expansion-panels>
        <v-expansion-panel v-for="(item, i) in itemss" :key="i">
          <v-expansion-panel-header>
            {{ item.title }}
          </v-expansion-panel-header>
          <v-expansion-panel-content v-for="(item, j) in item.items" :key="j">
            <span v-if="!item.items">{{ item.title }}</span>
            <template v-else>
              <v-expansion-panels>
                <v-expansion-panel>
                  <v-expansion-panel-header>
                    {{ item.title }}
                  </v-expansion-panel-header>
                  <v-expansion-panel-content v-for="(item, j) in item.items" :key="j">
                    <span>{{ item.title }}</span>
                  </v-expansion-panel-content>
                </v-expansion-panel>
              </v-expansion-panels>
            </template>
          </v-expansion-panel-content>
        </v-expansion-panel>
      </v-expansion-panels>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      selectedItem: null,
      items: [
        { text: 'Audience', icon: 'mdi-account' },
        { text: 'Real-Time', icon: 'mdi-clock' },
        { text: 'Conversions', icon: 'mdi-flag' },
      ],
      selected: [],
      islogin: true,
      list: [
        {
          title: 'title1',
          data: ['bdsadsad', 'bdsadsad', 'bdsadsad', 'bdsadsad']
        },
        {
          title: 'title2',
          data: ['bdsadsad', 'bdsadsad', 'bdsadsad', 'bdsadsad']
        },
        {
          title: 'title3',
          data: ['bdsadsad', 'bdsadsad', 'bdsadsad', 'bdsadsad']
        },
        {
          title: 'title4',
          data: ['bdsadsad', 'bdsadsad', 'bdsadsad', 'bdsadsad']
        },
        {
          title: 'title5',
          data: ['bdsadsad', 'bdsadsad', 'bdsadsad', 'bdsadsad']
        }
      ],
      itemss: [
        {
          items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }],
          title: 'Attractions',
        },
        {
          items: [
            { title: 'Breakfast & brunch' },
            {
              title: 'New American',
              items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }]
            },
            { title: 'Sushi' },
          ],
          title: 'Dining',
        },
        {
          items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }],
          title: 'Education',
        },
        {
          items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }],
          title: 'Family',
        },
        {
          items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }],
          title: 'Health',
        },
        {
          items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }],
          title: 'Office',
        },
        {
          items: [{ title: 'Sushi' }, { title: 'Sushi' }, { title: 'Sushi' }],
          title: 'Promotions',
        },
      ],
    }
  },
}
</script>
<style lang="scss">
  .pr-ads {
    height: 200px;
    width: 200px;
  border: 1px solid red;
}
.ct-select {
  .v-btn__content {
    .btn-ct {
      width: 100%;
    }
  }

  .v-btn[aria-expanded=true] {
    .icon-dropdown {
     transform: rotate(90deg);
    }
  } 
}

.footer {
  .v-expansion-panel::before {
    box-shadow: unset;
  }

  .v-expansion-panel:not(:first-child)::after {
    border-top: unset;
  }

  .v-expansion-panel-header {
    padding: 10px 20px 0 10px;
    border-bottom: 1px solid #333;
  }

  .v-expansion-panel--active>.v-expansion-panel-header {
    min-height: 55px;
  }

  .v-expansion-panel-content__wrap {
    padding: 10px 25px;
  }
}

.header {

  @media (max-width: 968px) {
    padding: 0 5px;
  }

  .logo-page {
    width: 170px;
  }

  &-search-area {
    &_form_title {
      border-right: 1px solid rgb(184, 183, 183);
      height: 400px;
      width: 200px;
      overflow: auto;

      .v-list--two-line .v-list-item {
        min-height: unset;
      }
    }

    &_form_options {
      height: 400px;
      width: 300px;
      overflow: auto;
      padding: 10px;

      .v-input--selection-controls {
        margin: 0;

        &__ripple>.v-ripple__container {
          visibility: hidden;
        }

        &__input {

          &:hover .v-input--selection-controls__ripple:before,
          &.primary--text .v-input--selection-controls__ripple:before {
            background-color: transparent;
          }
        }
      }
    }
  }

  &-search-category {
    .v-btn {
      border-radius: 0 25px 25px 0 !important;
    }

    &_form_options {
      height: 400px;
      width: 400px;
      overflow: auto;
      padding: 10px;

      .v-input--selection-controls {
        margin: 0;

        &__ripple>.v-ripple__container {
          visibility: hidden;
        }

        &__input {

          &:hover .v-input--selection-controls__ripple:before,
          &.primary--text .v-input--selection-controls__ripple:before {
            background-color: transparent;
          }
        }
      }
    }
  }

  .header_search {
    flex: 1;
    padding: 0 10px;
    justify-content: center;

    .header-button {
      max-width: 200px;
      width: 100%;
      display: block;

      .v-btn {
        padding: 0;
        width: 100%;
        text-align: center;
        border-radius: 25px 0 0 25px;
      }
    }

  }

  @media (max-width: 475px) {
    .header_tool .v-btn--icon.v-size--default {
      width: 24px;
      height: 24px;

      & .v-icon {
        font-size: 1rem;
      }
    }
  }

  /* Medium devices (landscape tablets, 768px and up) */
  @media only screen and (max-width: 768px) {
    .logo-page {
      width: 160px !important;
    }

    .header_search {
      .v-btn {
        // width: 150px !important;
      }
    }
  }

  /* Extra small devices (phones, 600px and down) */
  @media only screen and (max-width: 650px) {
    .logo-page {
      width: 150px !important;
    }

    .header_search {
      .v-btn {
        // width: 130px !important;
      }
    }
  }

  @media only screen and (max-width: 550px) {
    .logo-page {
      width: 130px !important;
    }

    .header_search {
      .v-btn {
        // width: 110px !important;
      }
    }
  }

  @media only screen and (max-width: 485px) {
    .logo-page {
      width: 80px !important;
    }

    .header_search {
      .v-btn {
        // width: 70px !important;
      }

      .v-btn.v-size--default {
        font-size: 10px;
      }
    }
  }
}
</style>