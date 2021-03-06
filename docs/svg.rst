SVG rendering
=============

The :mod:`chess.svg` module renders SVG Tiny images (mostly for IPython/Jupyter
Notebook integration). The piece images by
`Colin M.L. Burnett <https://en.wikipedia.org/wiki/User:Cburnett>`_ are triple
licensed under the GFDL, BSD and GPL.


.. autofunction:: chess.svg.piece

.. autofunction:: chess.svg.board

.. autoclass:: chess.svg.Arrow
    :members:

    .. py:attribute:: tail
        :type: chess.Square

        Start square of the arrow.

    .. py:attribute:: head
        :type: chess.Square

        End square of the arrow.

    .. py:attribute:: color
        :value: 'green'

        Arrow color.
