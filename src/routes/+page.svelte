<script>
	import { sql } from '@vercel/postgres';

	async function getData() {
		const { rows } = await sql`SELECT * FROM posts WHERE likes`;
	}
</script>

this is the book store
