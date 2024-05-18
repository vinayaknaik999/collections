<script lang="ts">
	import Activity from 'lucide-svelte/icons/activity';
	import ArrowUpRight from 'lucide-svelte/icons/arrow-up-right';
	import CircleUser from 'lucide-svelte/icons/circle-user';
	import Menu from 'lucide-svelte/icons/menu';
	import Package2 from 'lucide-svelte/icons/package-2';
	import Search from 'lucide-svelte/icons/search';

	import * as Avatar from '$lib/components/ui/avatar/index.js';
	import { Badge } from '$lib/components/ui/badge/index.js';
	import { Button } from '$lib/components/ui/button/index.js';
	import * as Card from '$lib/components/ui/card/index.js';
	import * as DropdownMenu from '$lib/components/ui/dropdown-menu/index.js';
	import { Input } from '$lib/components/ui/input/index.js';
	import * as Sheet from '$lib/components/ui/sheet/index.js';
	import * as Table from '$lib/components/ui/table/index.js';
	import Header from '$lib/layout/Header.svelte';
	import Toolbar from '$lib/layout/Toolbar.svelte';
</script>

<div class="flex flex-col h-full">
  <!-- Header -->
  <Header />
  <div class="flex flex-1">
      <!-- Toolbar -->
      <!-- <aside class="fixed w-14 bg-gray-200 h-full">
       
      </aside> -->

      <Toolbar />
      <!-- Main Content -->
      <main class="flex-1 bg-gray-100 h-full">
          <slot />
      </main>
  </div>
</div>
