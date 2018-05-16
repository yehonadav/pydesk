# pydesk is a desktop automation in python

# usage example:


from pydesk import desktop


#open a power point file

pptx = desktop.PPTX()

pptx.open('/path/to/pptx_file.pptx')


#enter presentation mode

pptx.start_presentation_mode()


#go over slides

pptx.next_slide(wait=2)

pptx.next_slide(wait=2)

pptx.next_slide(wait=2)

pptx.previous_slide(wait=2)

pptx.previous_slide(wait=2)

pptx.previous_slide(wait=2)

pptx.go_to_slide(2)


#exit

pptx.exit_presentation_mode()

pptx.close()


#go to other desktop window

desktop.switch_window(5)
