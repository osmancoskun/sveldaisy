<script>
	import { Button, Dropdown, DropdownAction, DropdownContent } from '$lib';
	let dropdowndatas = ['end', 'bottom', 'left', 'right', 'hover'];
</script>

<main class="h-screen w-screen flex justify-center items-center flex-col gap-y-5">
	<div>
		<Button primary>qwe</Button>
		<Button secondary>qwe</Button>
		<Button accent>qwe</Button>
		<Button ghost>qwe</Button>
		<Button link>qwe</Button>
		<Button info>qwe</Button>
		<Button success>qwe</Button>
		<Button warning>qwe</Button>
		<Button error>qwe</Button>
	</div>
	<div>
		<Button outline primary>qwe</Button>
		<Button outline secondary>qwe</Button>
		<Button outline accent>qwe</Button>
		<Button outline ghost>qwe</Button>
		<Button outline link>qwe</Button>
		<Button outline info>qwe</Button>
		<Button outline success>qwe</Button>
		<Button outline warning>qwe</Button>
		<Button outline error>qwe</Button>
	</div>
	<div>
		<Button lg primary>qwe</Button>
		<Button md secondary>qwe</Button>
		<Button sm accent>qwe</Button>
		<Button xs ghost loading>qwe</Button>
	</div>
	<div>
		<Dropdown>
			<DropdownAction>
				<Button>Dropdown</Button>
			</DropdownAction>
			<DropdownContent shadow rounded>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
			</DropdownContent>
		</Dropdown>
		<Dropdown left>
			<DropdownAction>
				<Button>Dropdown Left</Button>
			</DropdownAction>
			<DropdownContent shadow rounded>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
			</DropdownContent>
		</Dropdown>
		<Dropdown right>
			<DropdownAction>
				<Button>Dropdown right</Button>
			</DropdownAction>
			<DropdownContent shadow rounded>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
			</DropdownContent>
		</Dropdown>
		<Dropdown bottom>
			<DropdownAction>
				<Button>Dropdown bottom</Button>
			</DropdownAction>
			<DropdownContent shadow rounded>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
			</DropdownContent>
		</Dropdown>
		<Dropdown end>
			<DropdownAction>
				<Button>Dropdown end</Button>
			</DropdownAction>
			<DropdownContent shadow rounded>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
			</DropdownContent>
		</Dropdown>
		<Dropdown top>
			<DropdownAction>
				<Button>Dropdown top</Button>
			</DropdownAction>
			<DropdownContent shadow rounded>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
				<li>
					<a href="#">item1</a>
				</li>
			</DropdownContent>
		</Dropdown>
	</div>
	<div />
</main>
