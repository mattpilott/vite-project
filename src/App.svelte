<script lang="ts">
   import * as ContextMenu from './lib/ui/context-menu'
</script>

<main>
   <ContextMenu.Root>
      <ContextMenu.Trigger>
         <div
            class="grid transform rounded-[24px] bg-gradient-to-br from-zinc-50/25 to-zinc-50/5 to-50% p-[1px] transition duration-300 hover:scale-105"
         >
            <div
               class="grid aspect-video place-content-center place-items-center rounded-[23.5px] bg-zinc-900 text-white text-base"
            >
               Untitled
            </div>
         </div>
      </ContextMenu.Trigger>
      <ContextMenu.Content>
         <ContextMenu.Item href="/project">Present</ContextMenu.Item>
         <ContextMenu.Item>Rename</ContextMenu.Item>
         <ContextMenu.Item>
            <button type="submit" form="destroy">Delete</button>
         </ContextMenu.Item>
      </ContextMenu.Content>
   </ContextMenu.Root>
</main>
