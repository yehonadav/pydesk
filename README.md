# pydesk is a desktop automation in python

# usage example:


from pydesk import desktop

pptx = desktop.PPTX()

pptx.open('/path/to/pptx_file.pptx')

pptx.start_presentation_mode()

pptx.next_slide(wait=2)

pptx.next_slide(wait=2)

pptx.next_slide(wait=2)

pptx.previous_slide(wait=2)

pptx.previous_slide(wait=2)

pptx.previous_slide(wait=2)

pptx.go_to_slide(2)

pptx.exit_presentation_mode()

pptx.close()

desktop.switch_window(5)
